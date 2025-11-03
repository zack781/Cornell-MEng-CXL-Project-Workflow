<img src="https://github.com/zack781/Cornell-MEng-CXL-Project-Workflow/blob/main/CXL-Proj-Workflow.drawio.png" width="450" height="500">

On the Private Server:

Image Injection service (built with bash scripting and crontab for timer):
- Every 5 minutes, the service checks if there is a difference between the new rsync application code folder and the old one. If yes, it execs script to inject app code to image
