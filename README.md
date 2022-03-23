# covid-tracker
This is a dashboard for tracking coronavirus cases around the globe

### Teechnical Specification
- Java11
- SpringBoot
- Thymeleaf
- HTML
- BootStrap

### Description
- This app connects with datasource from Center for Systems Science and Engineering (CSSE) at Johns Hopkins University everyday by using Spring boot scheduler.
- Connection URL is in application.properties file
- It fetches latest metrics and populates on the dashboard.
- The data fetching is done by Java HTTP client.
- The HTTP responce is rendered by Thymeleaf.
- Bootstrap is used to make dashboard more presentable.
