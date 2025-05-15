# BlackboxNLP Main Website

This website handles the deployment of https://blackboxnlp.github.io. Since ad-hoc repositories are used to store contents from every edition of the workshop, this repository simply implements a redirect to the latest edition of the workshop.

## Setting up a new edition

1. Create a new repository for the edition, e.g., `2025`, by forking the previous year's repository.
2. Modify the information in the config to reflect the new edition program, organizers, dates and speakers.
3. Upon pushing changes in the repository, the `https://blackboxnlp.github.io/2025` subpage will be automatically updated with the new content.
4. Modify the `index.html` file here to redirect to the new repository.

For any information about handling the website, please contact Gabriele Sarti at [gabriele.sarti996@gmail.com](mailto:gabriele.sarti996@gmail.com)