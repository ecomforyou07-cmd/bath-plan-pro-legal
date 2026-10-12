# Account & Data Deletion — Bath Plan Pro (com.bathplanpro.app)

**Application Name:** Bath Plan Pro (`com.bathplanpro.app`)  
**Developer Support & Data Protection Contact:** rumenborisov500@gmail.com  

Users of **Bath Plan Pro** can permanently delete their account and all associated personal and project data at any time using either method below:

## Method 1: Instant Self-Service Deletion Inside the App
1. Open the **Bath Plan Pro** app and sign in to your account.
2. Open **Account & Plan** (`/account`).
3. Tap **Delete Account & Data** and confirm **Yes, Permanently Delete Everything**.
4. Your Firebase Authentication account, Cloud Firestore profile (`/users/{userId}`), and all saved bathroom projects (`/projects/{projectId}`) are deleted immediately.

## Method 2: Request Account Deletion Without Opening the App (Web / Email)
If you have already uninstalled the app, simply send an email from your registered email address to:
- **Email:** **rumenborisov500@gmail.com**
- **Subject:** `Account & Data Deletion Request — Bath Plan Pro`

## What Data Is Deleted vs. Retained
- **Permanently Deleted Immediately:**
  - Your Firebase Authentication user record (`uid`, email address, login credentials).
  - Your Cloud Firestore user profile document (`/users/{userId}`).
  - All saved 2D/3D bathroom projects, room layouts, tile calculations, and cost estimates (`/projects/{projectId}`).
- **Statutory Financial Records:**
  - If you purchased a subscription via Google Play, transaction receipts are retained by Google Play as required by applicable tax and accounting laws. Please cancel active subscriptions in the Google Play Store app under **Payments & subscriptions -> Subscriptions**.
