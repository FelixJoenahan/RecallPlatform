# RecallPlatform

A web platform for ANDtr employees to search medical device safety and
recall notices, save the relevant ones as a risk review, comment on them
and share them with customers.

Built for the Software Engineering module at Anglia Ruskin University.

## Features
- Employee and Customer accounts with different permissions
- Search recall notices by keyword
- Create risk reviews and add notices to them
- Comment on notices in a review
- Share a review with a customer
- Customers view and comment on reviews shared with them

## Tech stack
- C# and ASP.NET Core MVC (.NET 10)
- Entity Framework Core with SQL Server
- ASP.NET Core Identity for login and roles
- Bootstrap for the interface

## Getting started (Windows)
1. Install Visual Studio with the "ASP.NET and web development" workload.
2. Clone the repository with GitHub Desktop.
3. Open `RecallPlatform.slnx` in Visual Studio.
4. Press F5 to run.
5. Click Register. If a database error appears, click "Apply Migrations".

## How we work
- Each task is a GitHub Issue on the project board.
- Create a branch per issue, for example `feature/search-page`.
- Open a Pull Request and get one review before merging into `main`.
- Never commit directly to `main`.

## Team
- Felix Joenahan
- Avidan Soloman
- Olivia Wheeler
- Vatsal Ahir
- Abdul Rehman Khan