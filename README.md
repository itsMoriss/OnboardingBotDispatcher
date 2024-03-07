# HR Dispatcher Bot

This project contains the source code for the HR Dispatcher Bot, which automates the process of dispatching candidate information for onboarding.

## Description

The HR Dispatcher Bot is designed to read candidate information from an Excel file and add it to a queue in Orchestrator. It extracts essential details such as candidate ID, status, job title, full name, start date, acceptance deadline, and email address.

## Usage

1. Ensure that UiPath Studio is installed on your machine.
2. Clone this repository to your local machine.
3. Open the project in UiPath Studio.
4. Configure the project settings and dependencies as necessary.
5. Run the Main.xaml file to execute the bot.

## Dependencies

- UiPath Studio
- Orchestrator
- Excel Application

## File Structure

- **Main.xaml**: Main workflow file containing the sequence for reading candidate information and adding it to the queue.
- **Candidate Summary List.xlsx**: Sample Excel file containing candidate information.
