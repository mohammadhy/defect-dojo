# DefectDojo Upload Report 
The leading application vulnerability management tool.
Built for both DevSecOps and traditional application security
## Usage
1. Clone the repo:
    ```bash
    docker run -it 192.168.42.3:5000/defect-dojo:0.0.1 -url "http://192.168.42.12:8080" -api "6241eeb3e9f7ff818a4a6e976dedaa261dfae5ab" -product-id "1" -engagement-id "17" -scan-type "Trivy Scan" -engagement_name "ticket-servie" -file-path "trivy.json" -product-name "milad-255"
    ```
