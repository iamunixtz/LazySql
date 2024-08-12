# LazySql

***LazySql is an open-source tool designed for SQL injection testing. It offers robust functionality and is built to work effectively against high-security Web Application Firewalls (WAFs) like Kona Defender, Cloudflare, Envoy, and others***
```
python3 main.py -h


.____                           _________________  .____     
|    |   _____  ___________.__./   _____/\_____  \ |    |    
|    |   \__  \ \___   <   |  |\_____  \  /  / \  \|    |    
|    |___ / __ \_/    / \___  |/        \/   \_/.  \    |___ 
|_______ (____  /_____ \/ ____/_______  /\_____\ \_/_______ \
        \/    \/      \/\/            \/        \__>       \/


             LazySql - Noob SQL Injection Tool

usage: main.py [-h] [--tamper TAMPER] [--payloads PAYLOADS] [--databases DATABASES] [--waf WAF] [--threads THREADS] [--random-agents]
               [--time-sec TIME_SEC] [--delay DELAY] [--current-db] [--current-user] [--dump] [--columns] [--tables] [--banner]
               [--level LEVEL] [--risk RISK] [--r R]
               url param

LazySql is noob sqlinjection tool)

positional arguments:
  url                   The target URL to test (with vulnerable parameter)
  param                 The parameter to test for SQL Injection

options:
  -h, --help            show this help message and exit
  --tamper TAMPER       The tamper script to use (e.g. base64_tamper)
  --payloads PAYLOADS   The payload file to use (e.g. blind_payloads)
  --databases DATABASES
                        The database fingerprint file to use (e.g. mysql)
  --waf WAF             The WAF fingerprint file to use (e.g. mod_security)
  --threads THREADS     Number of threads for testing payloads
  --random-agents       Use random user agents
  --time-sec TIME_SEC   Time delay between requests in seconds
  --delay DELAY         Delay between requests in milliseconds
  --current-db          Get current database
  --current-user        Get current user
  --dump                Dump database contents
  --columns             Get column names
  --tables              Get table names
  --banner              Get database banner
  --level LEVEL         Set the injection level (1-5)
  --risk RISK           Set the injection risk (1-5)
  --r R                 Load requests from a file

```

**NB:Tool will be public available soon staying tune**








