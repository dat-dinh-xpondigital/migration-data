Migration Steps

- Install Docker: https://docs.docker.com/desktop/install/windows-install/
- Install VSCode & Docker extension: https://code.visualstudio.com/download
- Pull code from repository
- Change image tag to `ticket-id` or ask developer for image
- Run `docker compose up -d`
- Open `app` container in terminal
- Run `php artisan start:qa`
- If ask for google access token:
    - Open link in terminal
    - Authorize app
    - Parse google url to: https://www.freeformatter.com/url-parser-query-string-splitter.html
    - Copy code query parameter and paste into terminal
- Run command `php artisan export`
- Use VSCode to take report & export file: demo-docker => datjackson1997666/migration-data:{} => Files  => app => storage => temp
    - report: report-yyyy-mm-dd-h-m
    - Export: result-xxxxx.json 
