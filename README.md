# PublicTVLinks

Welcome to **PublicTVLinks**, a repository that provides a curated list of active TV streaming links in both M3U and JSON formats. These files (`active_tv_links.m3u` and `active_tv_links.json`) are automatically updated every 12 hours using a GitHub Actions workflow to ensure only working links are included.

## Files
- **`active_tv_links.m3u`**: An M3U playlist file containing active TV streams, categorized by genre (e.g., News, Sports, Movies), with channel names and logos.
- **`active_tv_links.json`**: A JSON file listing active TV streams with details like name, type ("Canal Aberto"), URL, and logo image.

## How It Works
- A private script fetches links from various public sources, verifies their activity, and generates these output files.
- The process runs every 12 hours (00:00 and 12:00 UTC) via GitHub Actions, pushing updates to this public repository.
- Only links responding with HTTP 200 status are included, ensuring reliability.

## Usage
1. **Download**: Grab the latest `active_tv_links.m3u` or `active_tv_links.json` from the repository.
2. **M3U**: Use with media players like VLC, IPTV apps, or Smart TVs supporting M3U playlists.
3. **JSON**: Integrate into custom applications or scripts needing structured data.

## Example
### `active_tv_links.m3u`
