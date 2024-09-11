# Slack Age Calculator Bot

A simple Slack bot written in Go that calculates a person's age based on their year of birth. This bot uses the `slacker` library to handle Slack commands and responds with the calculated age.

## Features

- **Slack Integration**: Connects to Slack using bot and app tokens.
- **Age Calculation**: Computes age from the year of birth provided in the command.
- **Command Event Logging**: Prints command events, including timestamps and parameters, for monitoring.

## Getting Started

To get started with this Slack bot, follow these steps:

### Prerequisites

- [Go](https://golang.org/doc/install) 1.19 or later
- A Slack workspace with permissions to create and manage Slack apps and bots.

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mohammedyunus2002/demo-repo.git
   cd demo-repo

   # Environment Variables

   Set up the following environment variables:
   
   ```env
   SLACK_BOT_TOKEN=xoxb-YOUR-BOT-TOKEN
   SLACK_APP_TOKEN=xapp-YOUR-APP-TOKEN
   ```
   
   ### Run the app
   ```bash
   go mod tidy
   go run main.go
   ```

