Firsthand is a privacy-focused platform that lets anonymous sources submit tips to journalists while proving their employment connection to the organization involved without revealing their identity.

## How It Works

1. A user privately verifies their employment connection.
2. Firsthand issues a non-transferable Verified Employment Credential.
3. The credential is stored in the user's credential wallet and can be reused.
4. When submitting a tip, the user attaches a credential as proof of their connection.
5. Journalists can verify the source's employment standing without seeing their identity or underlying records.

Firsthand verifies a source's connection to an organization, **not the truth of their allegation**.

## SBT Integration

Verified Employment Credentials are designed as Soulbound Tokens (SBTs). Because they are non-transferable, another person cannot acquire someone else's credential and falsely present themselves as a verified insider.

The blockchain and external employment verification are simulated in this prototype.

## Development

The initial frontend and interaction structure were generated using Figma Make. I manually implemented persistent credential storage using `localStorage` and duplicate credential detection so credentials can be stored and reused across sessions.
