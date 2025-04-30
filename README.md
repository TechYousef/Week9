
# 🚀 TourPlaces Deployment

This project contains the deployment setup for the **TourPlaces Inc.** frontend React application using a load-balanced architecture.

## 📁 Project Structure

- React frontend app
- Load balancer with multiple backend instances
- PowerShell and Bash support for testing
- Screenshots from Week 9

## 🧪 Test Load Balancing (PowerShell)

Use this command in PowerShell to test:

```powershell
for ($i = 1; $i -le 10; $i++) {
    curl http://<your-load-balancer-ip>/instance-id
    Start-Sleep -Seconds 1
}
```

Replace `<your-load-balancer-ip>` with your actual backend IP.

## 📸 Screenshots (Week 9)

### Instance ID Test

![Instance ID](Week9/screenshot1.png)

## 📝 Author

**TechYousef**

[GitHub Profile](https://github.com/TechYousef)
