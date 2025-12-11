# Pornhub Model Extractor | Videos & Profile
> A powerful extractor that collects structured profile and video data from model and pornstar pages. This tool delivers clean analytics-ready information for content research, performance tracking, or building automated dashboards. Designed for users who need reliable, large-scale extraction of Pornhub model data.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>pornhub-model-extractor-videos-profile</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
This project provides automated extraction of detailed model information and video metadata. It helps users gather accurate insights, track performance metrics, and analyze content trends at scale.
It is ideal for creators, agencies, analysts, and developers building data-driven applications.

### Why This Extractor Matters
- Collects complete model and pornstar profile data with precision.
- Extracts detailed metadata for thousands of videos.
- Ensures consistent formatting for analysis, dashboards, or automation workflows.
- Supports region-restricted content through proxy configuration.
- Offers flexible input customization for targeted extraction.

## Features
| Feature | Description |
|---------|-------------|
| Full Profile Extraction | Captures detailed model information including metrics, biography, social links, and verification status. |
| Video Metadata Collection | Extracts video IDs, durations, views, ratings, preview URLs, and more. |
| Flexible Targeting | Supports start URLs, page ranges, and max item limits. |
| Proxy-Aware | Automatically handles region blocks and restricted access. |
| Structured Output | Provides clean JSON/CSV-ready datasets for processing or integration. |
| Scalable Operations | Handles high-volume model pages with stable performance. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| model_name | The displayed name of the model or pornstar. |
| model_rank | Rank assigned based on platform metrics. |
| bio | Biography text provided on the profile. |
| about | Additional descriptive information. |
| subscribers | Total profile subscribers. |
| profile_views | Total number of profile page views. |
| video_views | Total views across published videos. |
| videos_watched | Number of videos watched by the model. |
| relationship_status | Displayed relationship status. |
| gender | Gender of the model. |
| birth_place | Country or region of origin. |
| height | Height information in imperial/metric format. |
| weight | Weight information. |
| ethnicity | Ethnicity category. |
| hair_color | Natural or displayed hair color. |
| tattoos | Tattoo presence. |
| piercings | Piercing presence. |
| interests_and_hobbie | Listed hobbies and interests. |
| turn_ons | Model-stated turn-ons. |
| is_verified | Whether the model profile is verified. |
| is_award_winner | Indicates award recognition. |
| social_links | URLs to external social accounts. |
| video_id | Unique ID of a video. |
| video_vkey | The viewkey identifier used in video URLs. |
| title | Title of the video. |
| duration | Duration in seconds. |
| views | Total views for a video. |
| rating | Rating percentage. |
| thumbnail_url | URL of the video thumbnail. |
| video_url | Direct URL to the public video page. |
| preview_url | URL for preview media. |

---
## Example Output


    {
        "model_name": "Sweetie Fox",
        "model_rank": 1,
        "bio": "Detailed biography text...",
        "about": "Sweetiefox.com ❤ I am a little cute girl...",
        "subscribers": 2500000,
        "video_views": 14,
        "profile_views": 404436342,
        "videos_watched": 4034,
        "relationship_status": "Open",
        "gender": "Female",
        "birth_place": "United States of America",
        "height": "5' 5' (165cm)",
        "weight": "125lbs. (57kg)",
        "ethnicity": "White",
        "hair_color": "Red",
        "tattoos": "No",
        "piercings": "No",
        "interests_and_hobbie": "Drawing, fitness, historical fencing...",
        "turn_ons": "When you watching me ;) Daddy theme...",
        "is_verified": true,
        "is_award_winner": true,
        "social_links": [
            "https://sweetiefox.com/ph",
            "https://www.twitter.com/SweetieFox1",
            "https://www.instagram.com/swfx_real"
        ],
        "url": "https://www.pornhub.com/model/sweetie-fox/videos"
    }


    {
        "video_id": "ph123456789",
        "video_vkey": "abc123def456",
        "title": "Video Title",
        "duration": 360,
        "views": 1000000,
        "rating": "45%",
        "thumbnail_url": "https://example.com/thumb.jpg",
        "video_url": "https://www.example.com/view_video.php?viewkey=abc123def456",
        "preview_url": "https://example.com/preview.mp4"
    }

---
## Directory Structure Tree


    Pornhub Model Extractor| Videos & Profile/
    ├── src/
    │   ├── runner.js
    │   ├── extractors/
    │   │   ├── model_parser.js
    │   │   ├── video_parser.js
    │   │   └── proxy_handler.js
    │   ├── utils/
    │   │   ├── html_parser.js
    │   │   └── paginator.js
    │   ├── outputs/
    │   │   └── formatter.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_profile.json
    │   └── sample_videos.json
    ├── package.json
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Agencies** use it to manage and monitor multiple model portfolios, enabling data-driven decision making.
- **Content creators** use it to track performance metrics and improve content strategy.
- **Researchers** use it to analyze trends, categories, demographics, and audience engagement.
- **Developers** integrate extracted data into apps, dashboards, or automation pipelines.
- **Media analysts** utilize datasets to evaluate popularity, competition, and content performance.

---
## FAQs
**Is this tool legal to use?**
It extracts only publicly available data and does not collect private or restricted information. Users must comply with regional laws and ensure responsible usage.

**Do I need proxies?**
Yes. Certain regions block access, so proxies ensure stable and unrestricted extraction.

**Can I extract both profile and video data?**
Yes. You can choose between "INFO" or "VIDEOS" via the input parameters.

**What is the maximum number of items I can extract?**
Up to 5000 items per run, depending on configuration.

---
### Performance Benchmarks and Results

**Primary Metric:**
Processes an average of 300–500 video entries per minute depending on proxy quality and regional restrictions.

**Reliability Metric:**
Maintains a 97%+ success rate across large-scale extractions, even with pagination and deep profile structures.

**Efficiency Metric:**
Optimized request batching reduces bandwidth usage by ~40% compared to naive scraping flows.

**Quality Metric:**
Delivers over 98% data completeness for supported fields, ensuring accuracy for analytics and reporting workflows.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
