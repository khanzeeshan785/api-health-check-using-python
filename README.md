# API Health Check

Perform health checks on API endpoints with this Python script. Simply specify the URL, HTTP method, and expected status code to monitor the health of your APIs.


## Key features
1. **Detailed Error Handling**: Added more descriptive error messages in case of request failures.
2. **Code Comments**: Included comments to explain the script functionality.
3. **Validation**: Added validations for the HTTP method and expected status code to ensure they are within valid ranges.
4. **Upper Case Method**: Ensured the HTTP method is converted to uppercase for consistency.
5. **Formatted Output**: Improved output formatting for clarity.

### Usage:
1. **Clone the repository**:
    ```
    git clone https://github.com/your-username/api-healthcheck.git
    ```

2. **Navigate to the project directory**:
    ```
    cd api-healthcheck
    ```

3. **Install dependencies** (if required):
    ```
    pip install -r requirements.txt
    ```

4. **Run the script**:
    ```
    python healthcheck.py --endpoint <API_URL> --method <HTTP_METHOD> --expected <EXPECTED_STATUS_CODE>
    ```

Replace `<API_URL>`, `<HTTP_METHOD>`, and `<EXPECTED_STATUS_CODE>` with the appropriate values for your API endpoint.

### Example:
```
python healthcheck.py --endpoint http://example.com/api --method GET --expected 200
```

This script will perform a health check on the specified API endpoint using the provided HTTP method and expected status code, then output the result.