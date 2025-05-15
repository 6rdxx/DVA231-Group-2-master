# QuizZLedge

A quiz application platform that allows users to create, join, and participate in quizzes.

## Vercel Deployment

This project has been configured for deployment on Vercel with PHP support.

### Deployment Steps

1. Connect your GitHub repository to Vercel
2. Select the repository in the Vercel dashboard
3. Configure the following settings:
   - Framework Preset: Other
   - Build Command: None
   - Output Directory: .
   - Install Command: None

4. Add the following environment variables if needed for database connection:
   - DB_HOST
   - DB_NAME
   - DB_USER
   - DB_PASSWORD

5. Deploy the project

### Local Development

To run this project locally:

```bash
# If you have PHP installed
php -S localhost:8000

# Navigate to http://localhost:8000 in your browser
```

## Project Structure

- `dashboard/` - Main dashboard and quiz listings
- `quiz/` - Quiz content and functionality
- `quiz-room/` - Live quiz room interface
- `registerlogin/` - User authentication
- `leaderboard/` - User rankings
- `create-quiz/` - Quiz creation interface
- `database/` - Database connection and queries
- `images/` - Static image assets
- `fonts/` - Typography assets
- `common/` - Shared components and functionality 