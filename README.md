# PublicTVLinks
![PublicTVLinks](https://m3uchecker.netlify.app/img/logo.png)

Welcome to **PublicTVLinks**, a repository that provides a curated list of active TV streaming links in multiple formats. These files (`active_tv_links.m3u`, `active_tv_links.json`, `active_tv_links.txt`, and `active_tv_links`) are automatically updated once every 24 hours using a GitHub Actions workflow to ensure only working links are included.

## Files
- **`active_tv_links.m3u`**: An M3U playlist file containing active TV streams, categorized by genre (e.g., News, Sports, Movies), with channel names and logos.
- **`active_tv_links.json`**: A JSON file listing active TV streams with details like name, type (category from source or "Free Air TV"), URL, and logo image.
- **`active_tv_links.txt`**: A TXT file in M3U format, identical to `active_tv_links.m3u`.
- **`active_tv_links`**: A file without extension in JSON format, identical to `active_tv_links.json`.

## How It Works
- A private script fetches links from 30 public sources, verifies their activity with improved reliability (HEAD with GET fallback, retries, and broader status acceptance), and generates these output files.
- The process runs daily at 00:00 UTC via GitHub Actions, pushing updates to this public repository.
- Only links confirmed active (e.g., HTTP 200 or 206) are included, optimized for offline streaming compatibility.

## Usage
1. **Download**: Grab the latest files from the repository.
2. **M3U/TXT**: Use `active_tv_links.m3u` or `active_tv_links.txt` with media players like VLC, IPTV apps, or Smart TVs supporting M3U playlists.
3. **JSON/No-Ext**: Use `active_tv_links.json` or `active_tv_links` in custom applications or scripts needing structured data.

## Example
### `active_tv_links.m3u` / `active_tv_links.txt`

## Direct links for use
- M3U    :<a href="https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links.m3u"> Right click & Copy link address </a>
- TXT    :<a href="https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links.txt"> Right click & Copy link address </a>
- JSON   :<a href="https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links.json"> Right click & Copy link address </a>
- W/O-EXT:<a href="https://raw.githubusercontent.com/bugsfreeweb/PublicTVLinks/refs/heads/main/active_tv_links"> Right click & Copy link address </a>

## Online Useable Tools:
<a href="https://hodlx.netlify.app" target="_blank"><img src="https://hodlx.netlify.app/img/logo.png" style="width:auto; height:60px" alt="IPTV Player"></a>
<a href="https://pismarttv.netlify.app" target="_blank"><img src="https://pismarttv.netlify.app/img/logo.png" style="width:auto; height:60px" alt="IPTV Player"></a>
<a href="https://hodliptv.netlify.app" target="_blank"><img src="https://hodliptv.netlify.app/img/logo.png" style="width:auto; height:60px" alt="IPTV Player"></a>
<a href="https://pixstream.netlify.app" target="_blank"><img src="https://pixstream.netlify.app/img/logo.png" style="width:auto; height:60px" alt="IPTV Player"></a>
<a href="https://m3uchecker.netlify.app" target="_blank"><img src="https://m3uchecker.netlify.app/img/logo.png" style="width:auto; height:60px" alt="M3U Checker"></a>

## Disclaimer
- No Content Hosting: This repository does not host or stream any content. It only aggregates publicly available streaming links.
- Third-Party Sources: Links are sourced from external, publicly accessible locations. We do not control, own, or maintain these streams.
- No Warranty: The links are provided "as is" without guarantees of availability, quality, or legality. Use at your own risk.
- Not Affiliated: This project is not affiliated with any streaming services, broadcasters, or content providers listed.
- Potential Risks: Streaming from unverified sources may expose you to legal, security, or privacy risks depending on your jurisdiction.
## Usage Policy
- Personal Use Only: These files are intended for personal, non-commercial use.
- No Redistribution for Profit: Do not redistribute or sell these files for commercial purposes.
- Respect Source Terms: Adhere to the terms of service of the original stream providers.
- Attribution: If you share or use this data, please credit bugsfreeweb/PublicTVLinks.
- Modification: Feel free to modify the files for personal use, but do not misrepresent them as official or endorsed content.
## Contributing
This is an automated project, so direct contributions are not accepted here. If you have suggestions or sources to add, please contact the maintainer via GitHub Issues (if enabled) or other means.

## License
This project is unlicensed in the public domain, but the content of the links remains subject to the original providers’ rights and terms.
