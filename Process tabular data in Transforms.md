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

# Pull Request Tips

- **Branch Management**
  - Ensure your branch is up to date with `master`.

- **Pull Request Title**
  - Provide a descriptive title for the PR.

- **Review**
  - Read through the PR to ensure it is clear and logical.

- **PR Description Checklist**
  - **Changes**: Clearly state what was changed in this PR.
  - **Build Links**: Include links to the build of the changes and any downstream dataset(s).
  - **Critical Datasets**: Provide a "Compare to master" link for critical datasets.
  - **Optional Analysis**: Include contour analysis for a deep dive into dataset content, if applicable.
  - **Follow-ups**: Note any potential follow-up tasks required after merging the PR.

- **Post-Merge Actions**
  - After merging, wait for checks to complete on `master`.
  - Consider running a build if necessary.

- **Ontology Datasets**
  - Ensure ontology datasets finish syncing before changes are visible.
