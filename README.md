# Project Router Chrome Extension

Auto-routes Claude.ai chats to 5 personal projects based on keyword matching with intelligent confidence scoring.

## 🚀 Quick Start

```bash
# Download and run the setup script
curl -fsSL https://raw.githubusercontent.com/adflickinger213/project-router-extension/main/setup.sh -o setup.sh
chmod +x setup.sh
./setup.sh
```

That's it! The script will:
- ✅ Create complete `project-router-extension/` directory
- - ✅ Generate all 6 JavaScript files with full source code
  - - ✅ Create popup.html with boho-cottagecore theme
    - - ✅ Set up manifest.json and styles.css
      - - ✅ Generate icon SVG files
        - - ✅ Provide Chrome loading instructions
         
          - ## 📋 Manual Installation
         
          - If you prefer manual setup, see `setup.sh` for the complete file structure.
         
          - ## 🎯 Projects
         
          - 1. **Dev & App Building** 💻 - React, GitHub, APIs
            2. 2. **FFFCU Work** 🏢 - Zoho, Sharepoint, Compliance
               3. 3. **Personal & Wellbeing** 💡 - Health, Home, Savings
                  4. 4. **Sims & Gaming** 🎮 - Mods, Gaming, Modding
                     5. 5. **Learning & Growth** 📚 - Certifications, PMs, Study
                       
                        6. ## ⚙️ How It Works
                       
                        7. - **≥95% confidence**: Auto-routes silently
                           - - **85-94% confidence**: Auto-routes + badge notification
                             - - **75-84% confidence or ties**: Flags for manual review
                               - - **<75% confidence**: Flags for review without suggestion
                                
                                 - ## 💾 Storage
                                
                                 - - Uses `chrome.storage.local` for all data
                                   - - Auto-purges entries older than 30 days
                                     - - Tracks routing history and statistics
                                      
                                       - ## 🎨 Theme
                                      
                                       - Boho-cottagecore design with:
                                       - - Dusty rose (#D4A5A5)
                                         - - Sage (#8FAF8A)
                                           - - Cream (#F5F1EE)
                                             - - Gold (#D4AF37)
                                              
                                               - ## License
                                              
                                               - MIT
