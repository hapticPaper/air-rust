# Air Rust Monitoring and Reporting
## git: air-rust

#### Python Flask backend API
Will accept 2 fundamental requests, GET and POST of sensor data. 
POST will accept the sensor reading of a single sensor.
    New data will be persisted for both immediate UI reporting, 
    but also esoteric reporting in the future (connection to postgres).
GET will return readings in chronologically descending order.