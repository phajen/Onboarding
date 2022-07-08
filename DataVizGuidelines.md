# Data Visualization Guidelines

Our intent is to provide general guidelines to use for data visualization - please use these guideliens unless you have a need or better idea. If you hvae a better idea, please provide feedback and suggestions for ways to improve our data viz guidelines and templates - we're always looking to improve.

- Read [Story Telling with Data](https://www.amazon.com/gp/product/1119002257/ref=as_li_qf_asin_il_tl?ie=UTF8&tag=storytellingwithdata-20&creative=9325&linkCode=as2&creativeASIN=1119002257&linkId=c9a5d9689e0665c8098acb1bd01b51e1)
  - Understand the **context** for the need to communicate
    - Who is your audience? What do you need them to know or do?
  - Choose effective visuals
  - Clutter is your enemy!
    - Identify the things that are taking up brain power unnecessarily and remove them
  - Focus your audience's attention
  - Think like a designer
    - Form follows function - what do we want our audience to be able to *do* with the data (function) and create a visualizatoin (form) that will allow for this with ease

- Textron Aviation brand guidelines
  - Proxima Nova or Arial font
    - Stick with Arial unless Proxima Nova is offered as default on the program so your font won't show up weirdly on other computers
  - Colors: #0077C8, #D50032, #75787B, #000000

- Pre-loaded data sources
  - D_Aircraft (BISQL)
    - SQL statement combines BSAP and CSAP aircraft, formats serial numbers consistently, and includes most of the relevant data fields
  - D_Calendar (BISQL)
  - D_Departments (BISQL)

- Power BI
  - [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
    - We're a Microsoft shop, so we primarily use Power BI for data viz
  - [Power BI Service Online Portal](https://app.powerbi.com/)
    - We utilize Power BI Service as a company to publish and share Power BI reports
    - **Workspaces** are mainly for collaboration and development, whereas [apps](https://app.powerbi.com/groups/me/apps) are meant for more finished products that are being used by others in production
  - Whenever you publish a Power BI report/app on Power BI Service, edit the settings to include a proper name, description, and contact details (advanced settings)

- General guidelines
  - Rename labels/field for visuals only, where applicable - nobody wants to see *FIN_YEAR* all over a report, use *Year* instead

- How to make dashboards that actually get used
  - Start with users, not with the data.
    - Don't just listen to users' requests, but instead engage in a conversatoin with them to get at the heart of their business needs.
    - Get curious and ask questions to explore the context around the users' requests. By exploring the deeper layers of a request, we can better undersatnd our users ann put together a more robust and targeted solution than what was originally requested.
  - Not just users first, but users throughout.
    - Instead of taking your first idea and building it out fully in Power BI, share your works in progress with the users (re-engaging)
  - Don’t build it and forget it. Build it and nurture it.
