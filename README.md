# 📷 Object Detection Using AWS Services

This project demonstrates how to perform **Object Detection** using **Amazon Rekognition**, a deep learning-based AWS service that can analyze images and return detailed label information.

## 🔍 Features

- Detects and displays all identifiable **objects, scenes, and concepts**.
- Provides **confidence scores** for each detected label.
- Shows **bounding box coordinates** for object positions.
- Identifies **parent labels** for hierarchical understanding.
- Interactive CLI-based Python script.

---

## ⚙️ Technologies Used

- **Python 3**
- **AWS Rekognition**
- **Amazon S3**
- **Boto3 (AWS SDK for Python)**

---

## 📁 How It Works

1. **Upload** your image to an AWS **S3 bucket**.
2. Run the script and **enter the image name** (including extension) when prompted.
3. The script:
   - Analyzes the image using Amazon Rekognition.
   - Returns:
     - Detected **labels** (objects).
     - **Confidence scores**.
     - **Bounding box dimensions**.
     - **Parent categories** (hierarchical).

---

## 🚀 Getting Started

### Prerequisites

- An AWS account with Rekognition and S3 permissions.
- AWS credentials configured (via AWS CLI or environment variables).
- Python 3 installed.

### Installation

```bash
pip install boto3
```

### Update the Bucket Name

In the script, replace:

```python
bucket = "your-s3-bucket-name"
```

with your actual **S3 bucket name**.

---

## 🧠 Example Output

```bash
Analyzing photo: car.jpg

Label: Car
Confidence: 98.67%
Bounding Box:
 - Top: 0.34
 - Left: 0.25
 - Width: 0.5
 - Height: 0.3
Parents:
 - Vehicle
-------------------------

Total Labels Detected: 8
```

---

## 💡 Use Cases

- Educational demos on **AWS Rekognition**.
- Building blocks for **image classification apps**.
- Quick prototypes for **AI-powered projects**.
- Real-time **object detection systems**.

---

## 📌 Notes

- Ensure the image is accessible in S3 with correct permissions.
- Avoid hardcoding sensitive information (use environment variables or config files).
- Recommended: Use `.env` for managing secrets securely in real-world projects.

---

## 👨‍💻 Author

**Sanavulla Baig**  
🎓 Final Year CSE Student, KL University  
🧠 AWS Certified Cloud Practitioner  
💻 MERN Stack & Python Enthusiast  
📫 [LinkedIn](https://www.linkedin.com/SanavullaBaig) | [GitHub](https://github.com/SanavullaBaig)

---

