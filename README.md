# Data Engineering for Manufacturing Operations

End-to-end data engineering process, including data quality audits and error remediation, integrations across disconnected data systems, and automated pipelines. 

Analytics and ML layers built on top, enabling real-time KPI monitoring, deep-dive diagnostics, root cause analyses, and machine learning forecasts embedded into existing systems.  

&nbsp;

## Project Folders

**[Defects & Scrap Costs](defects_scrap/)**

- Built on sheet-metal fabrication shop's data records (ERP, MES, QMS, Materials, HR)
- Cleans production, inspection, and material data records, integrates data source systems, and builds automated data pipeline flow
- Analytics diagnostic report details operating conditions that drive elevated defect rates
- KPI dashboard provides real-time view of defects and scrap costs  

&nbsp;

**[Downtime, OEE & Machine Health](downtime_oee/)**

- Built on precision machining shop's data records (MES, IIoT sensors, CMMS, ERP, HR)
- Cleans production, machine, and maintenance record data, integrates data source systems, and builds automated data pipeline flow
- KPI dashboard provides real-time monitoring of OEE and downtime, across the fleet and by machine
- Analytics diagnostic report details drivers of lost OEE by machine  
- ML model forecasts machine health indicators, embedded into CMMS system

&nbsp;

**[Job Costing](job_costing/)**

- Built on precision machining shop's data records (ERP and machine-monitoring sensors)
- Cleans ERP data records, integrates data systems, and builds automated data pipeline flow
- Job costing and margin analytics embedded into ERP system
- Analytics diagnostic report details job margin distributions, job cost overruns vs. estimates, and jobs that lost money    

&nbsp;

## Author

Brian Davis. Data engineering and applied analytics/ML for manufacturers. Other work: [github.com/bmdvs](https://github.com/bmdvs?tab=repositories).
