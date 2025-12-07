# Cloud Decode - AWS Learning Platform

A modern web platform showcasing AWS cloud computing expertise and deployment architecture.

## 🌐 Live Site

[awswithdevcom.pokhrelankit.com.np](http://awswithdevcom.pokhrelankit.com.np.s3-website-us-east-1.amazonaws.com/)

## 🏗️ Architecture

- **Hosting**: AWS S3 Static Website
- **Domain**: Route 53 DNS
- **CDN**: CloudFront Distribution
- **CI/CD**: GitHub Actions
- **SSL**: AWS Certificate Manager

## 🛠️ Tech Stack

- HTML5, CSS3, JavaScript
- Font Awesome Icons
- Google Fonts (Inter, JetBrains Mono)
- AWS Services Integration

## 📁 Project Structure

```
├── index.html          # Main landing page
├── error.html          # Custom 404 page
├── style/style.css     # AWS-themed styling
├── js/index.js         # Interactive features
├── assets/aws.png      # AWS branding
└── .github/workflows/  # Automated deployment
```

## 🚀 Features

- Responsive AWS-themed design
- Interactive service showcase
- Deployment architecture guide
- Mobile-optimized experience
- Custom 404 error handling

## 📋 AWS Services Covered

S3, EC2, RDS, Lambda, CloudFront, Route 53, IAM, VPC, Security Groups

## 🔧 S3 Bucket Policy

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": [
        "arn:aws:s3:::awswithdevcom.pokhrelankit.com.np/*",
        "arn:aws:s3:::awswithdevcom.pokhrelankit.com.np"
      ]
    }
  ]
}
```

## 🔗 Resources

- [AWS S3 Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html#S3Features)
- [Project Documentation](https://docs.google.com/document/d/1lBdoNP9MViLQNIcjZOwYEQ9qHeu1osvc/edit)

## 👨‍💻 Author

[Ankit Pokhrel](https://www.linkedin.com/in/ankitpokhrel/) - AWS Cloud Solutions Architect
