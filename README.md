# Getting Started with dbt on Snowflake

## Overview

This repository contains an example dbt project to get you started with dbt on Snowflake. 

# Important! Please Read The Following To Help You Finish The Setup Script To Run Successfully

For creating your DBT Project, you are required to create a Personal Access Token (PAT).
This can be accomplished with the following steps:

## Creating a Classic GitHub Personal Access Token

### Prerequisites
- A GitHub account with access to the repository
- Admin or write access to create and manage tokens

### Step-by-Step Instructions

1. **Navigate to GitHub Settings**
   - Go to [github.com](https://github.com) and log in to your account
   - Click your profile icon in the top-right corner
   - Select **Settings** from the dropdown menu

2. **Access Developer Settings**
   - In the left sidebar, scroll down and click **Developer settings**
   - Click **Personal access tokens** to expand the menu
   - Select **Tokens (classic)**

3. **Generate a New Token**
   - Click the **Generate new token (classic)** button
   - You may be prompted to confirm your password

4. **Configure Token Permissions**
   - **Token name**: Give your token a descriptive name (e.g., "dbt-snowflake-token")
   - **Expiration**: Select an appropriate expiration date or "No expiration"
   - **Scopes**: Check the following scopes:
     - `repo` - Full control of private repositories

5. **Generate and Save**
   - Click **Generate token** at the bottom of the page
   - **Important**: Copy your token immediately and save it securely (you won't be able to see it again)
   - Store it in a safe location (password manager, secure file, etc.)

### Using Your Token

Once you have your token, you can use it to create your secret in your DBT Project.


### Security Best Practices

- Never commit your token to version control
- Delete unused tokens promptly
- Use token expiration dates to limit exposure
- Consider using repository-specific tokens when possible
- Regenerate tokens regularly
- Monitor token usage in your GitHub audit log

### Troubleshooting

- **Token not working**: Verify the token hasn't expired and has the correct scopes
- **Permission denied**: Check that your token has the required scopes for your use case
- **Token regeneration needed**: If you suspect a token is compromised, delete it immediately and generate a new one

For more information, visit the [GitHub Personal Access Token documentation](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
