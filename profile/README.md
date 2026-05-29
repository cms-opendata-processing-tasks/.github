## Automated example workflows for CMS Open Data processing

This GitHub organization hosts examples of typical data processing tasks for CMS Open Data. 

They are intended as concrete examples on how to run processing tasks that might be needed when working on CMS Open Data. They are not examples of physics analyses, for those have a look in [CMS Open Data analyses and tools](https://github.com/cms-opendata-analyses) or [search](https://opendata.cern.ch/search?q=&f=experiment%3ACMS&f=type%3ASoftware%2Bsubtype%3AAnalysis&f=type%3ASoftware%2Bsubtype%3ATool&l=list&order=desc&p=1&s=10&sort=mostrecent) in the CERN Open Data portal.

Each repository provides a workflow definition, usable e.g. on public cloud, and provides an estimate of the time and resources needed for a becnhmarking process. We envisage implementing workflows using [Argo workflows](https://argoproj.github.io/workflows/) for Kubernetes clusters on public cloud resources, and eventually, [Snakemake](https://snakemake.readthedocs.io/en/stable/) for other executing environments.


