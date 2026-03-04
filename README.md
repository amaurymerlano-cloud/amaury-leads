\# 🚀 The Amaury Recommends: Affiliate Launchpad



Welcome to the open-source version of my \*\*Affiliate Launchpad\*\*. This system is designed to help you capture leads, educate your audience, and generate recurring affiliate commissions with zero hosting costs.



\## 📁 System Architecture

\- \*\*Capture Page (`index.html`):\*\* The entry point. Connects to Google Sheets.

\- \*\*Sales Page (`sales.html`):\*\* The conversion engine for MLGS.

\- \*\*Magazine Hub (`/blog/index.html`):\*\* Your authority content center.

\- \*\*The Guide (`/blog/guide.html`):\*\* The education piece that sells your toolbox.



---



\## 🛠 How to Clone This Business (5-Minute Setup)



\### 1. Fork this Repository

Click the \*\*"Fork"\*\* button at the top right of this page. This creates a copy of this entire website in your own GitHub account.



\### 2. Update Your Affiliate Links

You need to replace my IDs with yours so you get paid. Open these files in your GitHub editor:



\* \*\*`sales.html`\*\*: Find `rid=34110` and change it to \*\*your\*\* MLGS Affiliate ID.

\* \*\*`blog/guide.html`\*\*: 

&nbsp;   \* Replace the MLGS link with yours.

&nbsp;   \* Replace the \*\*Systeme.io\*\* link with your affiliate link.

&nbsp;   \* (Optional) Add your Namecheap affiliate link.



\### 3. Connect Your Google Sheet

To capture emails, you need your own "Backend":

1\. Create a Google Sheet.

2\. Go to \*\*Extensions > Apps Script\*\* and paste the `Code.gs` (provided in this repo).

3\. Deploy as a \*\*Web App\*\* (set access to "Anyone").

4\. Copy the Web App URL and paste it into `const SCRIPT\_URL` at the bottom of your `index.html`.



\### 4. Deploy to Cloudflare Pages (FREE)

1\. Log in to \[Cloudflare Pages](https://pages.cloudflare.com/).

2\. Select \*\*Connect to Git\*\* and choose your forked `amaury-leads` repo.

3\. Click \*\*Begin Setup\*\* > \*\*Save and Deploy\*\*.

4\. Your site is now live with unlimited bandwidth!



---



\## 📈 Recommended Strategy

1\. Send your daily MLGS leads to your \*\*Capture Page\*\*.

2\. Let the system redirect them to the \*\*Sales Page\*\*.

3\. Use the \*\*Launchpad Guide\*\* as your "Free Gift" in your follow-up emails.



\*\*Happy Earning!\*\*

