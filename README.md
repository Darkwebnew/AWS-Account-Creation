# EX - 1 CREATE AN ACCOUNT IN AWS SET UP A ROOT USER AND AN IAM USER

## 🧪 AIM
To create an AWS account, set up a root user, and create an IAM user with specified permissions to ensure secure and managed access to AWS resources.

---

## 📝 PROCEDURE

### Step 1: Create an AWS Account
- Visit [https://aws.amazon.com](https://aws.amazon.com)
- Click on **Create an AWS Account**
- Enter email, password, and AWS account name.

### Step 2: Log in as Root User
- Use the registered email and password.
- Access the AWS Management Console as the root user.

### Step 3: Configure Root User Security
- Enable **Multi-Factor Authentication (MFA)** for enhanced security.

### Step 4: Open IAM Management Console
- In the AWS Console, go to **Services > IAM**.

### Step 5: Add a New IAM User
- Click on **Users > Add user**
- Enter a unique username.
- Select **Programmatic access** and **AWS Management Console access**.

### Step 6: Set Permissions
- Attach existing policies (e.g., `AdministratorAccess`) or create a group with defined policies.

### Step 7: Review and Create
- Review all configurations.
- Click **Create User**.
- Download or copy the **Access Key ID** and **Secret Access Key**.

---

## 📸 OUTPUT

![image](https://github.com/user-attachments/assets/c9f6c53d-a161-49ef-8e47-12ecde5b18ab)

![image](https://github.com/user-attachments/assets/e78409ee-e66e-4186-82a9-de89577fc2f0)

## ✅ RESULT
The AWS account was successfully created. The root user was secured using multi-factor authentication, and a new IAM user was configured with necessary permissions, ensuring secure and controlled access to AWS services without exposing root credentials.
