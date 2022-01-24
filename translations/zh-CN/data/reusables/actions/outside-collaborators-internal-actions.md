If you make an internal repository in your enterprise accessible to {% data variables.product.prodname_actions %} workflows in other repositories, outside collaborators on the other repositories can indirectly access the internal repository, even though they do not have direct access to the internal repository. The outside collaborators can view logs for workflow runs when actions or workflows from the internal repository are used.