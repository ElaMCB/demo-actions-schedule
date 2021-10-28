# demo-actions-schedule

# How to run GitHub Actions on a Schedule

Workflows can be configured to run when specific activity occurs on GitHub, when an event outside of GitHub happens, or at a scheduled time. The schedule event allows to trigger a workflow to run at specific UTC times using POSIX cron syntax. 
This cron syntax has five * fields, and each field represents a unit of time.

The easiest way to determine CRON schedule is to use a https://crontab-generator.org/
