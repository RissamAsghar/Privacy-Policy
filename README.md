 # Privacy Policy for Med Folio                                                                                                                                                               
                                                                                                                                                                                                 
    **Effective Date:** October 14, 2026                                                                                                                                                         
    **Last Updated:** October 28, 2026                                                                                                                                                           
    **Developer:** Effitron                                                                                                                                                                      
    **Contact Email:** <a href="mailto:effitron.official@outlook.com?subject=Med%20Folio%20Privacy%20Inquiry">effitron.official@outlook.com</a>                                                  
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## Overview                                                                                                                                                                                  
                                                                                                                                                                                                 
    Effitron operates the **Med Folio** mobile application (the "App"). This Privacy Policy explains how we handle, process, store, and protect information when you use our educational medical 
    reference directory, package scanner, wellness calculators, reminders, Pomodoro timer, and study notebook tools.                                                                             
                                                                                                                                                                                                 
    We have designed Med Folio with an **offline-first, privacy-by-design architecture**. We do not operate proprietary external servers that collect, sell, or profile your personal health or  
    study data.                                                                                                                                                                                  
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 1. Information Processed Locally on Your Device                                                                                                                                           
                                                                                                                                                                                                 
    By default, all user-generated content and calculator inputs remain strictly on your device inside the App’s private internal storage:                                                       
                                                                                                                                                                                                 
    * **Notebook Content (Text, Checklists, Voice Notes, and Images):**                                                                                                                          
      Any study notes, checklists, voice recordings, and attached images (selected via the Android system Photo Picker) you create in the Notebook are stored locally in the App's private       
      internal storage (`filesDir` and local SQLite/Room database). We never have access to your notes, audio files, or images.                                                                  
    * **Body & Wellness Calculator Inputs:**                                                                                                                                                     
      Metrics entered into the calculators (such as height, weight, age, waist circumference, or heart rate) are calculated instantaneously in device memory to display educational outputs (BMI,
      BMR, TDEE, Ideal Body Weight, Hydration, and Heart Rate Zones). These values are not transmitted off your device.                                                                          
    * **Bookmarks, Reminders, and Pomodoro Timers:**                                                                                                                                             
      Saved formula/brand bookmarks, offline alarm schedules, and study timer sessions are stored locally on your device.                                                                        
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 2. Device Permissions & How We Use Them                                                                                                                                                   
                                                                                                                                                                                                 
    Med Folio requests specific Android permissions solely when you actively use a corresponding feature ("just-in-time" access):                                                                
                                                                                                                                                                                                 
    * **Camera (`android.permission.CAMERA`):**                                                                                                                                                  
      Requested only when you open the Smart Medicine Name & Barcode Scanner or capture an image for a note. Camera frames used for optical text recognition (OCR) and barcode scanning are      
      processed ephemerally 100% on-device to match package labels against the local drug directory. No camera video streams or scanned frames are ever uploaded or transmitted to any server.   
    * **Microphone (`android.permission.RECORD_AUDIO`):**                                                                                                                                        
      Requested solely when you actively tap the microphone button to use Voice Search or record a personal Audio Note inside your Notebook. Voice note files are saved exclusively inside the   
      App’s private local storage on your device. Background microphone recording is never performed.                                                                                            
    * **Location (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`):**                                                                                                                          
      Requested only when you actively open the Nearby Clinics & Pharmacies locator tab to find healthcare facilities around your current area on OpenStreetMap. Your location is used strictly  
      in real time while the screen is open and is never tracked in the background, stored, or sold.                                                                                             
    * **Biometric Authentication (`android.permission.USE_BIOMETRIC`):**                                                                                                                         
      Used locally via the Android OS `BiometricPrompt` hardware API to allow you to optionally lock private Notebook entries using your device fingerprint, face unlock, or screen lock PIN. The
      App only receives a boolean pass/fail result from the Android operating system and never accesses, reads, or stores your biometric data.                                                   
    * **Alarms & Notifications (`SCHEDULE_EXACT_ALARM`, `POST_NOTIFICATIONS`, `RECEIVE_BOOT_COMPLETED`):**                                                                                       
      Used strictly locally to ring your scheduled daily reminders and note alarms at the exact times and weekdays you configure, and to restore active alarms after your device reboots.        
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 3. Optional Backup & Cloud Restore Features                                                                                                                                               
                                                                                                                                                                                                 
    To prevent data loss when switching devices, Med Folio supports the following user-controlled backup options:                                                                                
                                                                                                                                                                                                 
    * **Android System Auto Backup:**                                                                                                                                                            
      If enabled in your device settings, the Android operating system automatically backs up lightweight app preferences and local database records (excluding heavy media files) to your       
      personal Google account.                                                                                                                                                                   
    * **Optional 1-Tap Google Drive Cloud Backup (`drive.appdata`):**                                                                                                                            
      If you voluntarily choose to use the "Back Up to Google Drive / Restore from Google Drive" feature, the App requests Google Sign-In authentication (accessing your basic account email/ID  
      for session authentication) and the restricted <a href="https://developers.google.com/drive/api/guides/api-specific-auth#app-data" target="_blank">drive.appdata</a> scope.                
    * **How Google Drive Data is Handled:**                                                                                                                                                      
      This scope only allows Med Folio to read and write your encrypted backup archive inside a hidden, private `appDataFolder` located within your own personal Google Drive account. Med Folio 
      cannot view, access, or modify any of your personal Google Drive files or folders, and your backup data never passes through any developer-owned server.                                   
    * **Manual Local Backup (`.zip` Export/Import):**                                                                                                                                            
      You may optionally export or import a `.zip` archive of your notes, audio recordings, and images using Android’s native Storage Access Framework (SAF) file picker without granting broad  
      storage permissions.                                                                                                                                                                       
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 4. Third-Party Services (Payments, Ads & Maps)                                                                                                                                            
                                                                                                                                                                                                 
    Med Folio integrates trusted third-party services that may collect limited device identifiers or process search queries governed by their own privacy policies:                              
                                                                                                                                                                                                 
    * **Google Play In-App Billing:**                                                                                                                                                            
      Subscription plans (Monthly, Yearly) and Lifetime PRO unlocks are processed securely by Google Play Billing. We do not see, collect, or store your credit card, debit card, or mobile      
      wallet numbers.                                                                                                                                                                            
      Policy: <a href="https://policies.google.com/privacy" target="_blank">https://policies.google.com/privacy</a>                                                                              
    * **Google AdMob (Free Tier Users Only):**                                                                                                                                                   
      For users on the free version, we use Google AdMob to display advertisements. AdMob may automatically collect your device’s Advertising ID, coarse IP address, and diagnostics data to     
      serve ads and prevent fraud. Upgrading to Med Folio PRO disables all advertisements.                                                                                                       
      Policy: <a href="https://policies.google.com/privacy" target="_blank">https://policies.google.com/privacy</a>                                                                              
    * **Google Play Services & On-Device ML Kit:**                                                                                                                                               
      Used for on-device optical text recognition (ML Kit OCR) to scan drug package names and barcodes locally, as well as optional Google Sign-In authentication for Google Drive cloud backup. 
                                                                                                                                                                                                 
      Policy: <a href="https://policies.google.com/privacy" target="_blank">https://policies.google.com/privacy</a>                                                                              
    * **OpenStreetMap (OSM) & Nominatim:**                                                                                                                                                       
      Used by the Nearby Clinics & Pharmacies locator to display interactive map tiles (via `osmdroid`) and search nearby healthcare facilities (via OpenStreetMap Nominatim and Overpass API).  
      Real-time location coordinates are queried directly against public OSM endpoints to return nearby results and are never tracked, logged, or saved.                                         
      Policy: <a href="https://wiki.osmfoundation.org/wiki/Privacy_Policy" target="_blank">https://wiki.osmfoundation.org/wiki/Privacy_Policy</a>                                                
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 5. Data Retention & How to Delete Your Data                                                                                                                                               
                                                                                                                                                                                                 
    Because you are in full control of your data, you can delete your information at any time:                                                                                                   
                                                                                                                                                                                                 
    * **Deleting Local Notes, Audio, Images & Reminders:**                                                                                                                                       
      You can delete individual notes, voice recordings, images, bookmarks, or alarms directly within the App at any time, or clear all local data via:                                          
      **Android Settings → Apps → Med Folio → Storage → Clear Storage** (or by uninstalling the App).                                                                                            
    * **In-App Cloud Deletion:**                                                                                                                                                                 
      Open **Med Folio → Settings / Account** and tap **"Delete Cloud Backup & Disconnect Google Drive."** This permanently deletes your backup file from your Google Drive `appDataFolder` and  
      revokes your Google Sign-In session.                                                                                                                                                       
    * **Via Your Google Account (Without the App):**                                                                                                                                             
      You can delete Med Folio’s hidden Drive data and revoke access anytime at:                                                                                                                 
      * <a href="https://myaccount.google.com/permissions" target="_blank">https://myaccount.google.com/permissions</a>                                                                          
      * Or inside <a href="https://drive.google.com" target="_blank">Google Drive (Web)</a> → **Settings → Manage Apps → Med Folio → Options → Delete hidden app data**.                         
    * **Via Email Request:**                                                                                                                                                                     
      If you need assistance disconnecting or deleting data, contact us at: <a href="mailto:effitron.official@outlook.com?subject=Data%20Deletion%20Request">effitron.official@outlook.com</a>   
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 6. Educational & Medical Disclaimer                                                                                                                                                       
                                                                                                                                                                                                 
    Med Folio is strictly an educational reference and study utility. It does not collect clinical Electronic Health Records (EHR), does not function as a medical device, and does not provide  
    medical advice, diagnosis, or treatment recommendations. Users are advised not to store identifiable third-party patient health records inside the personal study notebook.                  
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 7. Children's Privacy                                                                                                                                                                     
                                                                                                                                                                                                 
    Med Folio is intended for general audiences, students, and adult learners. We do not knowingly collect personal information from children under the age of 13.                               
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 8. Changes to This Privacy Policy                                                                                                                                                         
                                                                                                                                                                                                 
    We may update this Privacy Policy from time to time to reflect app updates or regulatory requirements. Any changes will be posted on this page with an updated "Last Updated" date.          
                                                                                                                                                                                                 
    ---                                                                                                                                                                                          
                                                                                                                                                                                                 
    ## 9. Contact Us                                                                                                                                                                             
                                                                                                                                                                                                 
    If you have any questions or concerns regarding this Privacy Policy or your data privacy, please contact us at:                                                                              
                                                                                                                                                                                                 
    * **Developer:** Effitron                                                                                                                                                                    
    * **Direct Email:** <a href="mailto:effitron.official@outlook.com?subject=Med%20Folio%20Privacy%20Inquiry">effitron.official@outlook.com</a>                                                 
    * **GitHub Repository:** <a href="https://github.com/RissamAsghar/Privacy-Policy" target="_blank">https://github.com/RissamAsghar/Privacy-Policy</a>                                         
  ──────                                                                                                                                                                                         
  ### 3. For GitHub Pages: index.html (If You Use a Web Page)                                                                                                                                    
                                                                                                                                                                                                 
  If your GitHub repository is published via GitHub Pages using an index.html file, you can copy this standalone, responsive HTML page directly into index.html:                                 
                                                                                                                                                                                                 
    <!DOCTYPE html>                                                                                                                                                                              
    <html lang="en">                                                                                                                                                                             
    <head>                                                                                                                                                                                       
      <meta charset="UTF-8">                                                                                                                                                                     
      <meta name="viewport" content="width=device-width, initial-scale=1.0">                                                                                                                     
      <title>Privacy Policy - Med Folio</title>                                                                                                                                                  
      <style>                                                                                                                                                                                    
        body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; line-height: 1.6; color: #24292e; max-width: 820px; margin: 40px auto; padding: 
        0 20px; background-color: #fafbfc; }                                                                                                                                                     
        .card { background: #ffffff; border: 1px solid #e1e4e8; border-radius: 12px; padding: 32px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); }                                                    
        h1 { color: #00695c; border-bottom: 2px solid #e1e4e8; padding-bottom: 12px; }                                                                                                           
        h2 { color: #004d40; margin-top: 28px; border-bottom: 1px solid #eaecef; padding-bottom: 8px; }                                                                                          
        a { color: #00796b; font-weight: 600; text-decoration: underline; }                                                                                                                      
        a:hover { color: #004d40; }                                                                                                                                                              
        .meta { background: #e0f2f1; padding: 12px 16px; border-radius: 8px; color: #004d40; font-weight: 500; margin-bottom: 24px; }                                                            
        table { width: 100%; border-collapse: collapse; margin: 16px 0; }                                                                                                                        
        th, td { border: 1px solid #e1e4e8; padding: 10px 14px; text-align: left; }                                                                                                              
        th { background: #f6f8fa; }                                                                                                                                                              
        code { background: #f3f4f6; padding: 2px 6px; border-radius: 4px; font-size: 0.9em; }                                                                                                    
      </style>                                                                                                                                                                                   
    </head>                                                                                                                                                                                      
    <body>                                                                                                                                                                                       
      <div class="card">                                                                                                                                                                         
        <h1>Privacy Policy for Med Folio</h1>                                                                                                                                                    
        <div class="meta">                                                                                                                                                                       
          <strong>Effective Date:</strong> October 14, 2026<br>                                                                                                                                  
          <strong>Last Updated:</strong> October 28, 2026<br>                                                                                                                                    
          <strong>Developer:</strong> Effitron<br>                                                                                                                                               
          <strong>Contact:</strong> <a href="mailto:effitron.official@outlook.com?subject=Med%20Folio%20Privacy%20Inquiry">effitron.official@outlook.com</a>                                     
        </div>                                                                                                                                                                                   
                                                                                                                                                                                                 
        <p>Effitron operates the <strong>Med Folio</strong> mobile application (the "App"). This Privacy Policy explains how we handle, process, store, and protect information when you use our 
        educational medical reference directory, package scanner, wellness calculators, reminders, Pomodoro timer, and study notebook tools.</p>                                                 
        <p>We have designed Med Folio with an <strong>offline-first, privacy-by-design architecture</strong>. We do not operate proprietary external servers that collect, sell, or profile your 
        personal health or study data.</p>                                                                                                                                                       
                                                                                                                                                                                                 
        <h2>1. Information Processed Locally on Your Device</h2>                                                                                                                                 
        <ul>                                                                                                                                                                                     
          <li><strong>Notebook Content:</strong> Notes, checklists, audio recordings, and attached images are stored locally in the App's private internal storage. We never have access to your 
          personal files.</li>                                                                                                                                                                   
          <li><strong>Wellness Calculators:</strong> Metrics entered (height, weight, age, etc.) are processed in volatile memory only.</li>                                                     
          <li><strong>Bookmarks & Reminders:</strong> Saved items, timers, and alarm schedules remain 100% on-device.</li>                                                                       
        </ul>                                                                                                                                                                                    
                                                                                                                                                                                                 
        <h2>2. Device Permissions & How We Use Them</h2>                                                                                                                                         
        <ul>                                                                                                                                                                                     
          <li><strong>Camera:</strong> Used strictly on-device for optical character recognition (OCR) and barcode scanning. Frames are never stored or uploaded.</li>                           
          <li><strong>Microphone:</strong> Used solely when recording a voice note or using voice search.</li>                                                                                   
          <li><strong>Location:</strong> Used in real time for Nearby Clinics & Pharmacies on OpenStreetMap. Location is never logged or tracked in the background.</li>                         
          <li><strong>Biometrics:</strong> Fingerprint/face unlock verification via Android hardware APIs. No biometric data is ever read or stored by the app.</li>                             
          <li><strong>Notifications & Alarms:</strong> Used locally for daily reminder schedules.</li>                                                                                           
        </ul>                                                                                                                                                                                    
                                                                                                                                                                                                 
        <h2>3. Backup & Cloud Restore Options</h2>                                                                                                                                               
        <ul>                                                                                                                                                                                     
          <li><strong>Google Drive AppData:</strong> Restricted to <code>https://www.googleapis.com/auth/drive.appdata</code>. Med Folio cannot access any personal Drive folders.</li>          
          <li><strong>Manual Backup:</strong> Offline <code>.zip</code> file export via Android's native file picker.</li>                                                                       
        </ul>                                                                                                                                                                                    
                                                                                                                                                                                                 
        <h2>4. Third-Party Services</h2>                                                                                                                                                         
        <table>                                                                                                                                                                                  
          <thead>                                                                                                                                                                                
            <tr><th>Service</th><th>Purpose</th><th>Privacy Policy</th></tr>                                                                                                                     
          </thead>                                                                                                                                                                               
          <tbody>                                                                                                                                                                                
            <tr><td>Google Play Billing</td><td>In-App Purchases & Subscriptions</td><td><a href="https://policies.google.com/privacy" target="_blank">Google Policy</a></td></tr>               
            <tr><td>Google AdMob</td><td>Ads for Free Tier Users</td><td><a href="https://policies.google.com/privacy" target="_blank">Google Policy</a></td></tr>                               
            <tr><td>Google Play Services & ML Kit</td><td>On-Device OCR & Sign-In</td><td><a href="https://policies.google.com/privacy" target="_blank">Google Policy</a></td></tr>              
            <tr><td>OpenStreetMap & Nominatim</td><td>Map Tiles & Location Search</td><td><a href="https://wiki.osmfoundation.org/wiki/Privacy_Policy" target="_blank">OSM Policy</a></td></tr>  
          </tbody>                                                                                                                                                                               
        </table>                                                                                                                                                                                 
                                                                                                                                                                                                 
        <h2>5. Data Retention & Deletion</h2>                                                                                                                                                    
        <p>You can delete your information at any time:</p>                                                                                                                                      
        <ul>                                                                                                                                                                                     
          <li><strong>Local Data:</strong> Delete notes/reminders in-app, or via Android Settings → Apps → Med Folio → Clear Storage.</li>                                                       
          <li><strong>Google Drive Backup:</strong> In Med Folio, tap <em>"Delete Cloud Backup & Disconnect"</em>, or revoke permissions at <a href="https://myaccount.google.com/permissions"   
          target="_blank">https://myaccount.google.com/permissions</a>.</li>                                                                                                                     
          <li><strong>Email Request:</strong> Contact us at <a href="mailto:effitron.official@outlook.com?subject=Data%20Deletion%20Request">effitron.official@outlook.com</a>.</li>             
        </ul>                                                                                                                                                                                    
                                                                                                                                                                                                 
        <h2>6. Medical Disclaimer</h2>                                                                                                                                                           
        <p>Med Folio is strictly an educational reference and study utility. It does not provide medical advice, diagnosis, or clinical Electronic Health Record management.</p>                 
                                                                                                                                                                                                 
        <h2>7. Contact Us</h2>                                                                                                                                                                   
        <p>Email: <a href="mailto:effitron.official@outlook.com?subject=Med%20Folio%20Privacy%20Inquiry">effitron.official@outlook.com</a><br>                                                   
        Repository: <a href="https://github.com/RissamAsghar/Privacy-Policy" target="_blank">https://github.com/RissamAsghar/Privacy-Policy</a></p>                                              
      </div>                                                                                                                                                                                     
    </body>                                                                                                                                                                                      
    </html>     
