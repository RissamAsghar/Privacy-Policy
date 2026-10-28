 Privacy Policy for Med Folio                                                          
                                                                                         
  Effective Date: October 14, 2026                                                       
  Last Updated: October 28, 2026                                                         
  Developer: Effitron                                                                    
  Contact Email: effitron.official@outlook.com                                           
  ──────                                                                                 
  ## Overview                                                                            
                                                                                         
  Effitron operates the Med Folio mobile application (the "App"). This Privacy Policy    
  explains how we handle, process, store, and protect information when you use our       
  educational medical reference directory, package scanner, wellness calculators,        
  reminders, Pomodoro timer, and study notebook tools.                                   
                                                                                         
  We have designed Med Folio with an offline-first, privacy-by-design architecture. We do
  not operate proprietary external servers that collect, sell, or profile your personal  
  health or study data.                                                                  
  ──────                                                                                 
  ## 1. Information Processed Locally on Your Device                                     
                                                                                         
  By default, all user-generated content and calculator inputs remain strictly on your   
  device inside the App’s private internal storage:                                      
                                                                                         
  • Notebook Content (Text, Checklists, Voice Notes, and Images):                        
  Any study notes, checklists, voice recordings, and attached images (selected via the   
  Android system Photo Picker) you create in the Notebook are stored locally in the App's
  private internal storage (filesDir and local SQLite/Room database). We never have      
  access to your notes, audio files, or images.                                          
  • Body & Wellness Calculator Inputs:                                                   
  Metrics entered into the calculators (such as height, weight, age, waist circumference,
  or heart rate) are calculated instantaneously in device memory to display educational  
  outputs (BMI, BMR, TDEE, Ideal Body Weight, Hydration, and Heart Rate Zones). These    
  values are not transmitted off your device.                                            
  • Bookmarks, Reminders, and Pomodoro Timers:                                           
  Saved formula/brand bookmarks, offline alarm schedules, and study timer sessions are   
  stored locally on your device.                                                         
  ──────                                                                                 
  ## 2. Device Permissions & How We Use Them                                             
                                                                                         
  Med Folio requests specific Android permissions solely when you actively use a         
  corresponding feature ("just-in-time" access):                                         
                                                                                         
  • Camera (android.permission.CAMERA):                                                  
  Requested only when you open the Smart Medicine Name & Barcode Scanner or capture an   
  image for a note. Camera frames used for optical text recognition (OCR) and barcode    
  scanning are processed ephemerally 100% on-device to match package labels against the  
  local drug directory. No camera video streams or scanned frames are ever uploaded or   
  transmitted to any server.                                                             
  • Microphone (android.permission.RECORD_AUDIO):                                        
  Requested solely when you actively tap the microphone button to use Voice Search or    
  record a personal Audio Note inside your Notebook. Voice note files are saved          
  exclusively inside the App’s private local storage on your device. Background          
  microphone recording is never performed.                                               
  • Location (ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION):                            
  Requested only when you actively open the Nearby Clinics & Pharmacies locator tab to   
  find healthcare facilities around your current area on OpenStreetMap. Your location is 
  used strictly in real time while the screen is open and is never tracked in the        
  background, stored, or sold.                                                           
  • Biometric Authentication (android.permission.USE_BIOMETRIC):                         
  Used locally via the Android OS BiometricPrompt hardware API to allow you to optionally
  lock private Notebook entries using your device fingerprint, face unlock, or screen    
  lock PIN. The App only receives a boolean pass/fail result from the Android operating  
  system and never accesses, reads, or stores your biometric data.                       
  • Alarms & Notifications (SCHEDULE_EXACT_ALARM, POST_NOTIFICATIONS,                    
  RECEIVE_BOOT_COMPLETED):                                                               
  Used strictly locally to ring your scheduled daily reminders and note alarms at the    
  exact times and weekdays you configure, and to restore active alarms after your device 
  reboots.                                                                               
  ──────                                                                                 
  ## 3. Optional Backup & Cloud Restore Features                                         
                                                                                         
  To prevent data loss when switching devices, Med Folio supports the following user-    
  controlled backup options:                                                             
                                                                                         
  • Android System Auto Backup:                                                          
  If enabled in your device settings, the Android operating system automatically backs up
  lightweight app preferences and local database records (excluding heavy media files) to
  your personal Google account.                                                          
  • Optional 1-Tap Google Drive Cloud Backup (drive.appdata):                            
  If you voluntarily choose to use the "Back Up to Google Drive / Restore from Google    
  Drive" feature, the App requests Google Sign-In authentication (accessing your basic   
  account email/ID for session authentication) and the restricted https://www.googleapis.com/auth/drive.appdata scope.                                                          
  • How Google Drive Data is Handled:                                                    
  This scope only allows Med Folio to read and write your encrypted backup archive inside
  a hidden, private appDataFolder located within your own personal Google Drive account. 
  Med Folio cannot view, access, or modify any of your personal Google Drive files or    
  folders, and your backup data never passes through any developer-owned server.         
  • Manual Local Backup (.zip Export/Import):                                            
  You may optionally export or import a .zip archive of your notes, audio recordings, and
  images using Android’s native Storage Access Framework (SAF) file picker without       
  granting broad storage permissions.                                                    
  ──────                                                                                 
  ## 4. Third-Party Services (Payments, Ads & Maps)                                      
                                                                                         
  Med Folio integrates trusted third-party services that may collect limited device      
  identifiers or process search queries governed by their own privacy policies:          
                                                                                         
  • Google Play In-App Billing:                                                          
  Subscription plans (Monthly, Yearly) and Lifetime PRO unlocks are processed securely by
  Google Play Billing. We do not see, collect, or store your credit card, debit card, or 
  mobile wallet numbers.                                                                 
  Policy: https://policies.google.com/privacy                                            
  • Google AdMob (Free Tier Users Only):                                                 
  For users on the free version, we use Google AdMob to display advertisements. AdMob may
  automatically collect your device’s Advertising ID, coarse IP address, and diagnostics 
  data to serve ads and prevent fraud. Upgrading to Med Folio PRO disables all           
  advertisements.                                                                        
  Policy: https://policies.google.com/privacy                                            
  • Google Play Services & On-Device ML Kit:                                             
  Used for on-device optical text recognition (ML Kit OCR) to scan drug package names and
  barcodes locally, as well as optional Google Sign-In authentication for Google Drive   
  cloud backup.                                                                          
  Policy: https://policies.google.com/privacy                                            
  • OpenStreetMap (OSM) & Nominatim:                                                     
  Used by the Nearby Clinics & Pharmacies locator to display interactive map tiles (via  
  osmdroid) and search nearby healthcare facilities (via OpenStreetMap Nominatim and     
  Overpass API). Real-time location coordinates are queried directly against public OSM  
  endpoints to return nearby results and are never tracked, logged, or saved.            
  Policy: https://wiki.osmfoundation.org/wiki/Privacy_Policy                             
  ──────                                                                                 
  ## 5. Data Retention & How to Delete Your Data                                         
                                                                                         
  Because you are in full control of your data, you can delete your information at any   
  time:                                                                                  
                                                                                         
  • Deleting Local Notes, Audio, Images & Reminders:                                     
  You can delete individual notes, voice recordings, images, bookmarks, or alarms        
  directly within the App at any time, or clear all local data via:                      
  Android Settings → Apps → Med Folio → Storage → Clear Storage (or by uninstalling the  
  App).                                                                                  
  • In-App Cloud Deletion:                                                               
  Open Med Folio → Settings / Account and tap "Delete Cloud Backup & Disconnect Google   
  Drive." This permanently deletes your backup file from your Google Drive appDataFolder 
  and revokes your Google Sign-In session.                                               
  • Via Your Google Account (Without the App):                                           
  You can delete Med Folio’s hidden Drive data and revoke access anytime at:             
      • https://myaccount.google.com/permissions                                         
      • Or inside https://drive.google.com → Settings → Manage Apps → Med Folio → Options
      → Delete hidden app data.                                                          
  • Via Email Request:                                                                   
  If you need assistance disconnecting or deleting data, contact us directly at:         
  effitron.official@outlook.com                                                          
  ──────                                                                                 
  ## 6. Educational & Medical Disclaimer                                                 
                                                                                         
  Med Folio is strictly an educational reference and study utility. It does not collect  
  clinical Electronic Health Records (EHR), does not function as a medical device, and   
  does not provide medical advice, diagnosis, or treatment recommendations. Users are    
  advised not to store identifiable third-party patient health records inside the        
  personal study notebook.                                                               
  ──────                                                                                 
  ## 7. Children's Privacy                                                               
                                                                                         
  Med Folio is intended for general audiences, students, and adult learners. We do not   
  knowingly collect personal information from children under the age of 13.              
  ──────                                                                                 
  ## 8. Changes to This Privacy Policy                                                   
                                                                                         
  We may update this Privacy Policy from time to time to reflect app updates or          
  regulatory requirements. Any changes will be posted on this page with an updated "Last 
  Updated" date.                                                                         
  ──────                                                                                 
  ## 9. Contact Us                                                                       
                                                                                         
  If you have any questions or concerns regarding this Privacy Policy or your data       
  privacy, please contact us at:                                                         
                                                                                         
  • Developer: Effitron                                                                  
  • Support Email: effitron.official@outlook.com                                         
  • GitHub Repository: https://github.com/RissamAsghar/Privacy-Policy                    
                                                                       
