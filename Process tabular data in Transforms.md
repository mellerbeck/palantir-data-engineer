###                                                           Connecting Data
Foundry's tools for connecting to data support the full range of standard enterprise data sources, ranging from cloud-based object stores, file systems, and databases and data warehouses.

Connect to sources to run batch, streaming, media, and CDC syncs and to use virtual tables

What are batch

What are streaming

What are media

What are CDC

What is a dataset

A dataset is the most essential representation of data from when it lands in Foundry through when it is mapped into the Ontology. 
<img src="https://github.com/user-attachments/assets/92023662-4e9e-4d14-a721-311d76d049c4" width="250"/>

What are code repositories (Best Practices for code repositories)

https://www.youtube.com/watch?v=XEZ-bTtW8Z4

Go to settings, branches to configure which groups of people can approve the PR

Pull request tips
  Branch should be up to date with master
  Give PR a descriptive title
  Read over PR to make sure it makes sense
  PR description checklist
    what did you change in this PR
    Link to build of the changed + downstream dataset(s)
    For critial dataset: 'Compare to master' link
    Optional: Contour analysis to deep dive into dataset content
    Potential follows ups necessary after merging your PR
  After merging, wait for checks on master, potentially run build
  Ontology datasets must finish syncing before seeing changes

    
