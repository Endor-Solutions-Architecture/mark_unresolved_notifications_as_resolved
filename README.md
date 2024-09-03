Step 1: create .env file  

API_KEY=<your_api_key_here>  
API_SECRET=<your_api_secret_here>  
ENDOR_NAMESPACE=<your_namespace>  

Step 2: run

```
python3 -m venv venv  
source venv/bin/activate  
pip install -r requirements.txt  
```

Step 3:
Mark all notifications that are un resolved as resolved:
```
python3 main.py 
```


