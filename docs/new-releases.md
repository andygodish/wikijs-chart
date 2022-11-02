# Creating New Releases

For the sake of running my own chart repository in my homelab, I occasionally check the upstream (requarks/wiki) chart for updates. Updated version of the wikijs chart are pulled into a new branch and pushed to this repo. That branch is then merged into the main branch. From there, the release.yaml workflow can be triggered to create a new release based on the extracted version found in the Chart.yaml.

The version comes from the upstream helm chart pushed into its own branch. 
