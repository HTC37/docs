After you connect your account on {% data variables.product.prodname_dotcom_the_website %} to the {% data variables.product.prodname_github_codespaces %} extension, you can create a new codespace. For more information about the {% data variables.product.prodname_github_codespaces %} extension, see the [{% data variables.product.prodname_vs_marketplace_shortname %}](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces).

{% data reusables.codespaces.click-remote-explorer-icon-vscode %}
1. Hover over the "Remote Explorer" sidebar and click {% octicon "plus" aria-label="The plus icon" %}.

   ![Screenshot of the "Remote Explorer" sidebar for {% data variables.product.prodname_github_codespaces %}. The tooltip "Create New Codespace" is displayed beside the plus sign button.](/assets/images/help/codespaces/create-codespace-vscode.png)

1. In the text box, type the name of the repository you want to develop in, then select it.

   ![Screenshot of "octo-org/he" entered into the text box and a list of four repositories that start with this string.](/assets/images/help/codespaces/choose-repository-vscode.png)

   If the repository you choose is owned by an organization, and the organization has configured codespaces for this repository to be billable to the organization, or its parent enterprise, a message will be displayed in subsequent prompts telling you who will pay for the codespace.

1. Click the branch you want to develop on.
1. If prompted to choose a dev container configuration file, choose a file from the list.
1. Click the machine type you want to use.

   {% note %}

   **Note**: {% data reusables.codespaces.codespaces-machine-type-availability %}

   {% endnote %}
