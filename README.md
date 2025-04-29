# How to Get a DOI for a GitHub Repository Using Zenodo
A DOI (Digital Object Identifier) is a permanent identifier useful for citing your GitHub project in academic publications. Here's how to set one up with Zenodo:

## 1. Create a Zenodo account
Go to https://zenodo.org/.

Click Sign up and create an account (or log in if you already have one).

## 2. Link your GitHub account to Zenodo
After logging into Zenodo, click your profile icon in the top-right corner, then Account Settings.

Under Linked Accounts, find GitHub and click Connect.

Authorize Zenodo to access your GitHub repositories.

## 3. Enable GitHub repository for DOI generation
Once your GitHub account is connected, go to the GitHub tab under your Zenodo settings.

You’ll see a list of your repositories.

Flip the switch ON for the repository you want to assign a DOI to.

Note: You must have write access to the GitHub repository to enable DOI integration.

## 4. Create a GitHub Release
Go back to your GitHub repository.

Click on Releases > Draft a new release.

Tag the release (e.g., v1.0.0), fill out the release title and description, and Publish release.

Important: Zenodo automatically creates a snapshot of the repository at the time of the release — make sure your repo is ready!

## 5. Zenodo archives the release and issues a DOI
After the release is published, Zenodo will automatically archive the release and mint a DOI.

It may take a few minutes. You can check your Zenodo dashboard under Uploads to see the new entry.

## 6. (Optional) Customize the metadata
Zenodo lets you edit metadata (title, authors, keywords, funding information) for the record.

This is useful to make your citation more complete and professional.

## 7. Add the badge to your GitHub README
Zenodo will generate a badge (Markdown snippet) you can add to your README to show the DOI.



## Quick Tips
Each new GitHub release will generate a new versioned DOI automatically.

You get a concept DOI (referring to all versions) and a version-specific DOI (referring to a particular snapshot).

Make sure you tag releases correctly following semantic versioning (v1.0.0, v1.1.0, etc.).
