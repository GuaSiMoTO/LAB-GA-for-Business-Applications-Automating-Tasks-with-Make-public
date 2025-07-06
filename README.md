# LAB-GA-for-Business-Applications-Automating-Tasks-with-Make

![](https://github.com/user-attachments/assets/31ee7a4e-a57d-4d54-8351-9cbde7505a74)

### **Activities**

1. **Task 1: Sending Personalized Emails from Google Sheets**
   You need to email a set of clients with personalized messages containing their names and details.

   - **Exercise**:  
     - Create a Google Sheet with **2–3 rows** including sample emails and names. You can use your own or classmates’ emails (with consent).  
     - Build a scenario in **Make** to read each row and send an email via Gmail.  
     - Use variables to insert the recipient’s name in the message.  
     - Test by sending to the sample emails to verify personalization.

   - **Example Google Sheet:**

     | Email                 | Name       |
     |-----------------------|------------|
     | example1@gmail.com    | Alice      |
     | example2@gmail.com    | Bob        |

2.1 **Task 2.1: Creating Calendar Events for Annual Marketing Campaigns**
   You need to prepare your marketing calendar by automatically creating events for important dates.

   - **Exercise**:  
     - Create a Google Sheet listing at least **5 key marketing dates** (example below).  
     - Build a scenario in **Make** to read the sheet and create Google Calendar events.  
     - Test to ensure all events appear with the correct details.

   - **Example Google Sheet:**

     | Event Name            | Description                      | Date       | Time     |
     |-----------------------|----------------------------------|------------|----------|
     | New Year Campaign     | Launch January promotions       | 2025-01-02 | 09:00 AM |
     | Valentine's Campaign  | Promote Valentine's offers      | 2025-02-10 | 09:00 AM |
     | Summer Sale Kickoff   | Start summer discounts          | 2025-06-01 | 09:00 AM |
     | Black Friday Planning | Prepare Black Friday strategy   | 2025-10-15 | 09:00 AM |
     | Holiday Campaign      | Launch Christmas promotions     | 2025-12-01 | 09:00 AM |

2.2 **Task 2.2: Sync Calendar Events with the Google Sheet (Add, Update, Delete)**
   Your marketing calendar must always reflect the current rows in the Google Sheet—adding, updating, or removing events.

   - **Exercise**:  
     - Create a scenario in **Make** that watches the same Google Sheet for any changes.  
     - For each detected change:  
       - **Add** a new event if a row is newly created.  
       - **Update** an event if any details are modified (e.g., date, description).  
       - **Delete** the event if the row is removed.  
     - Test by adding, editing, and deleting rows to confirm the Calendar reflects all changes correctly.


3. **Task 3: Saving Incoming Emails to Google Drive**
   Your company wants to archive all incoming emails with attachments for record-keeping.

   - **Exercise**:  
     - Create an automation in **Make** to watch Gmail for new emails with attachments.  
     - Save attachments into a designated Google Drive folder.  
     - Test to ensure files are saved correctly.

4. **Task 4: Scheduling Classes with Meet Links**
   You need to automate the creation of Google Meet meetings for each planned class and generate corresponding Google Calendar events.

   - **Exercise**:  
     - Create a Google Sheet listing your planned classes for a week (example below).  
     - Build a scenario in **Make** that:  
       - Reads each row.  
       - Creates a Google Calendar event **with a Meet link**.  
       - Sets title, description, date, and time based on the sheet.  
     - **Important**: Before creating the event, ensure it does **not** already exist in Calendar or Meet to avoid duplicates.
     - Test by verifying events appear in your Google Calendar and include the Meet link.

   - **Example Google Sheet:**

     | Class Title            | Description                       | Date       | Start Time | Duration (minutes) |
     |------------------------|-----------------------------------|------------|------------|---------------------|
     | Introduction to AI     | Overview of AI concepts          | 2025-07-08 | 10:00 AM   | 60                  |
     | Machine Learning Basics| Supervised/unsupervised learning | 2025-07-09 | 10:00 AM   | 90                  |
     | Neural Networks        | Deep learning introduction       | 2025-07-10 | 10:00 AM   | 90                  |
     | AI Ethics              | Responsible AI practices         | 2025-07-11 | 10:00 AM   | 60                  |
     | Project Workshop       | Hands-on project session         | 2025-07-12 | 10:00 AM   | 120                 |

---

## Bonus

b1. **Task: Automating Meeting Summaries and Notifications**
     After each marketing meeting recorded on Google Meet, the following steps need to happen automatically:
     - Transcription and summarization with AI tools.
     - Summaries are emailed to all team members.

b2. **Task: Automating Social Media Post Scheduling**
   The marketing team has a Google Sheet with planned posts for SmartBuddy’s social media campaign. Automate the scheduling process using Make.

b3. **Task: Automating Issue Tracking from Incoming Emails**
When a new issue report email arrives, you want to detect the issue details and create a record in your project management platform automatically.

---

### **Expected Deliverables**
- **Scenario Files**: Screenshots or export files of the scenarios created in Make. Put them in `student_deliverables` folder.
