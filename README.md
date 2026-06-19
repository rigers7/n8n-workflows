# n8n Workflows

This repository documents a collection of workflow projects I develop with
[n8n](https://n8n.io/). Each project demonstrates a different automation,
integration, or business process built to solve a practical use case.

## Repository structure

Each workflow is stored in its own folder and may include:

- An importable n8n workflow file in JSON format
- A screenshot or diagram of the workflow
- Supporting documentation and setup notes

## Using a workflow

To try a workflow, download its JSON file and import it into your n8n instance.
You may need to configure credentials, environment variables, integrations, and
other settings for your own environment before activating it.

## Security

Credentials and secrets are not included in the workflow exports. Always review
a workflow before importing it, use appropriately restricted credentials, and
avoid committing API keys, passwords, or other sensitive information.

## Disclaimer

These workflows are shared for documentation, learning, and inspiration. Test
them carefully before using them in a production environment.
