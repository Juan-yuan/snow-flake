## Let's start
1. run command to init project: python3 -m venv .
2. install snowflake-connector-python: pip3 install snowflake-connector-python
3. activate project: source bin/activate
4. login into your snow flake account, create a database: 
![alt text](image.png)
5. run command to connect your snow flake: python3 snow_sample.py -u kittyyuan -p Shanjun@007 -a jahbpox-fo48556 -t CRIME_LITE -f crime2.csv -d NO
![alt text](image-1.png)
6. check snow flake, we can see the tables, stages and file firmats are there:
![alt text](image-2.png)
7. select CRIME_LITE table values and stages:
![alt text](image-3.png)
![alt text](image-4.png)
8. create a .env file with values:
  SF_USER=kittyyuan
  PASSWORD=Shanjun@007
  ACCOUNT=jahbpox-fo48556
  TABLE=CRIME_LITE
  FILE=crime2.csv
  TRUNCATE=YES
9. install package run command:  pip3 install python-dotenv
![alt text](image-5.png)
10. run command to execute snow_sample_env.py file, command: python3 snow_sample_env.py
![alt text](image-6.png)