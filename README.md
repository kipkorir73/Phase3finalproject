# Gym Membership Management System

## Introduction
This project is a Gym Membership Management System that allows you to manage gym members, record attendance, track billing, and perform various operations related to gym membership management. It is built using Python, SQLAlchemy, and Click for the command-line interface (CLI). With this system, you can easily manage your gym's membership database and related activities.

## Features
The Gym Membership Management System includes the following features:

1. **Member Management:** Create, update, and delete gym member records, including their names and membership status.

2. **Attendance Recording:** Record attendance for gym members, including the date and member's name.

3. **Billing Management:** Add and update billing details for gym members, including the billing amount and payment date.

4. **Database Initialization:** Initialize the database with necessary tables for gym members, attendance, and billing.

5. **List Members:** View a list of all gym members, including their IDs, names, and membership status.

6. **List Billing Details:** View billing details for a specific gym member, including billing IDs, amounts, and payment dates.

7. **Command-Line Interface:** The system features a user-friendly CLI powered by Click, making it easy to interact with the application.

## Getting Started
To use this Gym Membership Management System:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Set up the database connection URL by updating the `DATABASE_URL` variable in `cli.py` with your database URL.
4. Initialize the database by running `python cli.py init-db`.
5. Use the CLI commands to manage gym members, attendance, and billing (see CLI Commands section).

## CLI Commands
The following CLI commands are available for managing your gym membership system:

- `add-member`: Add a new gym member.
- `delete-member`: Delete a gym member.
- `update-member`: Update gym member details.
- `record-attendance`: Record attendance for a gym member.
- `add-billing`: Add billing for a gym member.
- `update-billing`: Update billing details for a gym member.
- `list-members`: List all gym members.
- `list-billing`: List billing details for a gym member.
- `init-db`: Initialize the database.

To execute a command, use `python cli.py COMMAND`, where `COMMAND` is one of the available commands listed above.

## Prerequisites
Ensure you have the following prerequisites installed on your system:

- Python
- SQLAlchemy
- Click

## Support and Contact Details
If you have any questions, suggestions, or would like to contribute to this project, please feel free to contact the author:

- Email: kipkorirc583@gmail.com

## License
Copyright (c) 2023 Collins Kipkorir.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
