Generic response object that includes the peer id retrieved from get_call_parameters inside the service. 
```
pub struct AMResponse {
    pub success: bool,
    pub result_raw: String,
    pub result: String,
    pub timestamp: i64,
    pub host_id: String
}
```
