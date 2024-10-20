# Faction Example Report Templates
You can use these templates to start converting your own reports over to Faction. 

## Community Reports
All reports in this section can be used by all versions of Faction both free and paid
- __default-report-template__: This is the default template that Faction loads on start up. It uses DOCX tables to report vulnerability findings. 
- __default-report-wo-tables__: This report is identical to __default-report-templete__ except it reports findings using the `${fiBegin}` and `${fiEnd}` tags instead DOCX tables. Anything between these two variables will be repeated for each finding.
- __default-template-cvss-score__: This report is identical to __default-report-template__ except it uses CVSS scoring instead of Faction's native scoring.


## Enterprise Reports
All reports in this section implement additional features only available in paid versions of Faction.
- __default-report-template-sections-enterprise__: This report implements the Section Feature Faction and allows you to have different sections for findings. For Example: Application Security Assessment and Network Security Assessments. 
- __default-report-wo-tables-sections-enterprise__: This report implements the Section Feature Faction and allows you to have different sections for findings. For Example:  Application Security Assessment and Network Security Assessments. This uses the `${fiBegin Section}` and `${fiEnd Section}` tags to report findings in different sections. 

