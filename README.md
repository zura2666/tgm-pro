Download the app from the release file
TGM Pro

A multi-account Telegram management toolkit designed for automated group scraping, member statistics, campaign scheduling, and bulk operations.
TGM Pro includes a desktop application and a lightweight web companion for managing Telegram workflows from a single dashboard.

Features
Accounts Manager

Add and manage multiple Telegram accounts.

View logged-in vs total accounts.

Quick authentication flow with session tracking.

Smart Scraper

Scrape member lists from target Telegram groups.

Track total scraped members, daily counts, and scrape status.

Export results for reuse in other features.

Member Adder

Add scraped members to your own groups.

View daily add statistics with success/failure breakdown.

Announcement Scheduler

Schedule and send broadcast messages to channels or groups.

Organize campaigns through a clean and structured UI.

Track execution logs and delivery status.

License System

Integrated license manager with tier-based feature unlocking.

In-app activation panel and license information view.

User Interface

Dark, modern layout with tabs for:

Accounts

Settings

Scraper

Adder

Announcer

Header stats: active accounts, members added today, and more.

Unified design across desktop and web companion.

Installation
Desktop Application

Download the latest release from the Releases section.

Extract the archive.

Run the executable file.

Log in with your Telegram accounts following the on-screen instructions.

Web Companion (Optional)

The web companion runs alongside the desktop app.
Instructions and configuration can be found in the /docs directory (recommended to add this to your repo).

Usage Overview
1. Add Accounts

Open Accounts tab.

Add Telegram sessions.

Ensure sessions remain active.

2. Scrape Members

Open Scraper.

Enter a target group link.

Start scraping and monitor the dashboard.

3. Add Members to Your Group

Move to the Adder tab.

Load scraped lists.

Configure add limits.

Start the operation.

4. Schedule Broadcasts

In Announcer, create a campaign.

Set target channels/groups.

Choose broadcast time and content.

Technical Overview

A high-level architecture (you can modify based on your actual stack):

Desktop App: Electron

Backend: Node.js

Database: SQLite for session and data storage

Telegram API: MTProto client libraries

Web Companion: Lightweight server exposing local endpoints



Roadmap

API rate optimization

Improved captcha handling

Parallel scraping engine

Plugin system for custom workflows

Cloud sync for settings and campaigns

License

Specify your license here (MIT, GPL, proprietary, etc.).

Support

For issues or feature requests, use the GitHub Issues tab.
