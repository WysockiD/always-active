# auto-commit 🟩 🟩 🟩 🟩

Using [Github Actions](https://github.com/features/actions) to keep your tiles green! Auto commits at 9 and 5 every day! 🪴🥬

Create your own repo
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `email` and `name` information on file [autocommit.yml, line 27 and 28](https://github.com/WysockiD/auto-commits/blob/main/.github/workflows/autocommit.yml#L27)
- Change the scheduling time on file [autocommit.yml, line 9](https://github.com/WysockiD/auto-commits/blob/main/.github/workflows/autocommit.yml#L9). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` (But once you set up and make any commit it will run right away, if it runs fine first time, it will run via your scheduling from then).

