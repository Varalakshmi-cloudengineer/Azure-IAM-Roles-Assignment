# Azure IAM - Custom Role and Role Assignment

## ✅ Project Title: Day9-Azure-IAM-Roles-Assignment

### 📌 Objective:
To create a custom IAM role in Azure and assign it to a user with limited permissions on a resource group.

---

## 🛠️ Steps Performed:

1. **Opened Azure Portal** and navigated to the Subscriptions section.
2. **Created a custom role** named `ReadOnly-Storage-Access` with:
   - `Microsoft.Storage/storageAccounts/read`
   - `Microsoft.Resources/subscriptions/resourceGroups/read`
3. **Created a new Azure Active Directory user** (or used an existing one).
4. **Assigned the custom role** to the user at the resource group level using IAM (Access Control).

---

## 🎯 Outcome:
User now has read-only access to storage accounts and resource groups, as per the custom role permissions.

---

## 📁 Screenshots:
All screenshots were captured during execution and saved locally.

---

## 🔐 Notes:
This simulates real-world role-based access control used in production for developers/testers to follow least privilege principle.
