**English** | [简体中文](README_zh.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# Stylus Web Reading

This project provides separate Stylus CSS styles for Feishu documents, Gemini, and ChatGPT. They refine the appearance of text, headings, lists, code, and tables. Install only the styles you need.

| Website | Style file | Stylus domain |
| --- | --- | --- |
| Feishu | [feishu-v1.0.css](01_Feishu/feishu-v1.0.css) | `feishu.cn` |
| ChatGPT | [chatgpt-v1.0.css](02_ChatGPT/chatgpt-v1.0.css) | `chatgpt.com`, `chat.openai.com` |
| Gemini | [gemini-v1.0.css](03_Gemini/gemini-v1.0.css) | `gemini.google.com` |

## Usage Guide

### Before and After

Each image shows the same scene side by side: the original display on the left and the Stylus style on the right.

#### Feishu

![Feishu document before and after applying the Stylus style](image/Feishu_Compare.png)

#### ChatGPT

![ChatGPT before and after applying the Stylus style](image/ChatGPT_Compare.png)

#### Gemini

![Gemini before and after applying the Stylus style](image/Gemini_Compare.png)

### Prerequisites

- Install the Stylus extension in Chrome or Edge.
- For the intended appearance, install the Inter, HarmonyOS Sans SC, JetBrains Mono, and Fira Code fonts. Your browser will fall back to system fonts if they are unavailable. The font files are included in this repository's [fonts/](fonts/) directory; install the `.ttf` files using your operating system's font installer.

### Installation and Configuration

1. If you are new to Stylus, start with the [video tutorial](https://www.bilibili.com/video/BV1aRXzBYErj). It uses Feishu as the example; for ChatGPT or Gemini, use the corresponding CSS file and domain. Then search for **Stylus** in the Chrome or Edge extension store and install it.

   ![Find Stylus in the extension store](image/Stylus_Install.png)

2. Click the Stylus icon in the browser toolbar and select **Manage**.

   ![Open the Stylus management page](image/Stylus_Manage.png)

3. Select **Write new style**. Create a separate style for each website.

   ![Create a Stylus style](image/Stylus_CreateStyle.png)

4. Open the corresponding `.css` file in the table above and paste its full contents into the Stylus editor.

   ![Paste the CSS source](image/Stylus_PasteCSS.png)

5. Under **Applies to**, choose **URLs on the domain** and enter the domain from the table. For ChatGPT, add a rule for each domain if you need both.

   ![Set the Stylus domain](image/Stylus_SetDomain.png)

6. Check the style name, **Enabled**, and **Live preview** settings. Confirm that **Custom included sites** contains only the relevant domain; **Custom excluded sites** can remain empty. The screenshot shows the Feishu example.

   ![Review the Stylus settings](image/Stylus_CheckSettings.png)

7. Click **Save**, then refresh the target website to see the result.

## Background and Contact

I was a second-year university student focused on embedded systems when I started this project. I enjoyed using Feishu and created the first style with AI assistance, even though frontend development was not my field. I later found the same approach useful for ChatGPT and Gemini, so I split the project into three independent styles.

My time for maintenance is limited, and the project still has issues. For example, bold headings inside Feishu code blocks may overflow. Feedback and code contributions are welcome.

Thanks to the **Stylus extension** and its developers for providing the user style manager that makes these CSS styles easy to install and use.

### Feedback and Bug Reports

- GitHub Issues: [Report an issue or bug](https://github.com/jacelee-embdev/stylus-web-reading/issues)
- Email: [jacelee.embdev@gmail.com](mailto:jacelee.embdev@gmail.com)
- Feishu: [Add me as a contact](https://www.feishu.cn/invitation/page/add_contact/?token=ea6n748d-ae1f-4026-8b11-be387b677dcf)

## License

This project is licensed under the **MIT License**.

Copyright (c) 2026 JesMicro. See the [LICENSE](LICENSE) file in the repository root for the full license text.
