# automate_youtube_with_spotify

This project is an AWS Lambda function that syncs your liked videos from YouTube to a Spotify playlist. It uses the YouTube Data API to fetch liked videos and the Spotify API to search for songs and add them to a new playlist. Authentication is handled via OAuth 2.0, and secrets are securely managed using AWS Secrets Manager.
