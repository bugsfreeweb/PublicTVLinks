# PublicTVLinks

Welcome to **PublicTVLinks**, a repository that provides a curated list of active TV streaming links in both M3U and JSON formats. These files (`active_tv_links.m3u` and `active_tv_links.json`) are automatically updated every 12 hours using a GitHub Actions workflow to ensure only working links are included.

## Files
- **`active_tv_links.m3u`**: An M3U playlist file containing active TV streams, categorized by genre (e.g., News, Sports, Movies), with channel names and logos.
- **`active_tv_links.json`**: A JSON file listing active TV streams with details like name, type ("Free Air Channel"), URL, and logo image.

## How It Works
- A private script fetches links from various public sources, verifies their activity, and generates these output files.
- The process runs every 12 hours (00:00 and 12:00 UTC) via GitHub Actions, pushing updates to this public repository.
- Only links responding with HTTP 200 status are included, ensuring reliability.

## Usage
1. **Download**: Grab the latest `active_tv_links.m3u` or `active_tv_links.json` from the repository.
2. **M3U**: Use with media players like VLC, IPTV apps, or Smart TVs supporting M3U playlists.
3. **JSON**: Integrate into custom applications or scripts needing structured data.

## Direct links for use
For M3U   : [https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links.m3u] .
For JSON  : [https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links.json] .

## Online Use:


## Disclaimer
No Content Hosting: This repository does not host or stream any content. It only aggregates publicly available streaming links.
Third-Party Sources: Links are sourced from external, publicly accessible locations. We do not control, own, or maintain these streams.
No Warranty: The links are provided "as is" without guarantees of availability, quality, or legality. Use at your own risk.
Not Affiliated: This project is not affiliated with any streaming services, broadcasters, or content providers listed.
Potential Risks: Streaming from unverified sources may expose you to legal, security, or privacy risks depending on your jurisdiction.

## Usage Policy
Personal Use Only: These files are intended for personal, non-commercial use.
No Redistribution for Profit: Do not redistribute or sell these files for commercial purposes.
Respect Source Terms: Adhere to the terms of service of the original stream providers.
Attribution: If you share or use this data, please credit bugsfreeweb/PublicTVLinks.
Modification: Feel free to modify the files for personal use, but do not misrepresent them as official or endorsed content.

## Contributing
This is an automated project, so direct contributions are not accepted here. If you have suggestions or sources to add, please contact the maintainer via GitHub Issues (if enabled) or other means.

## License
This project is unlicensed in the public domain, but the content of the links remains subject to the original providers’ rights and terms.
