# Nucleus SDK
Nucleus SDK with instructions and examples on how to use Nucleus APIs

## Python SDK Generation
1. Follow instructions on https://github.com/swagger-api/swagger-codegen to install Swagger Code Generator
  * MacOS:   
    `brew install swagger-codegen`

2. Run Swagger Code Generator to generate Nucleus client Python module
  * MacOS:  
    ```
    cd swagger
    swagger-codegen generate -i nucleus-api-swagger.json -l python -c config.json -o sdk
    ```

3. Install Nucleus client Python module. This step assumes that you are running python from a Python3 virtual environment
```
cd sdk
python3 setup.py install
```

4. Test Nucleus API with an example
  * Go to the examples directory `cd ../../examples`
  * Open analyze-trump-tweets.py in a text editor and update the lines below with provided host name and API key  
    ```
    configuration.host = 'API_HOST_HERE'
    configuration.api_key['x-api-key'] = 'API_KEY_HERE'
    ```
  * Execute the example: 'python3 analyze-trump-tweets.py' 