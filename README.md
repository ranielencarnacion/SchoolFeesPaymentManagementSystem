# School Fees Payment Management System

![ECA Logo](./eca-logo.png)

Hey! This is my school project in Business Management - a website where schools can keep track of student fees and payments. Basically, instead of using paper records, everything is stored digitally and you can easily see who paid what and when like tuition fees, school fees etc.

## What it does

- You can add new students to the system
- Set up different courses with their own fees
- Record when students make payments
- Check payment history for any student
- Secure admin area (only authorized people can access)

## What you'll need to run this

- **XAMPP** - This gives you everything (Apache server, PHP, and MySQL database)
- Any web browser (Chrome, Firefox, etc.)
- That's pretty much it!

## Setting it up (step by step)

1. **Get XAMPP** - Download it from their website and install it
2. **Start the servers** - Open XAMPP control panel and start Apache and MySQL
3. **Copy the files** - Put this whole folder into `C:\xampp\htdocs\`
4. **Set up the database**:
   - Go to `http://localhost/phpmyadmin` in your browser
   - Create a new database called `sfps_db`
   - Go to the Import tab and upload the `.sql` file from the `database/` folder
5. **Test it out** - Visit `http://localhost/School_Fees_Payment_Management_System`

## Default login info

**Username:** admin  
**Password:** admin123

*(Make sure to change this password once you're in!)*

## Project structure

```
├── index.php          # Home page
├── admin/             # All the admin pages
├── database/          # Database backup file
├── assets/            # CSS styles, JavaScript, images
└── README.md          # This file
```

## Database setup

The system uses these main tables:
- **users** - Stores admin login info
- **student** - All student details
- **courses** - List of available courses
- **fees** - How much each course costs
- **payments** - Records of all payments made

## Important notes

This was built as a school assignment, so it's pretty basic but functional. If you're using this for real, definitely change the admin password and maybe add some extra security features.

Got questions? Feel free to ask!
