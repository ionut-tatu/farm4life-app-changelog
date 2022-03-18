# Change Log
All notable changes to this project will be documented in this file.

## v1.4.0
### Added
 - Added videos assigned by module endpoint, to display on Playlist page
 - Remove from Learning feature (both employee & employer)
 - Added error message when submitting quiz without answer
 
### Fixed
 - Revamped Playlist page template
 - Assigned video doesn't show immediately under Playlist
 - User profile doesn't update upon making changes
 - User profile picture doesn't update in top navbar
 - Module not showing total & completed duration, progress bar not working
 - Video without a quiz still showing 0/1 complete
 - App crashes when quiz is submitted without an answer
 - Changing between accounts will show the previous account profile picture


## v1.3.7
### Added

### Fixed
 - Fixed API refresh token upon getting 401 and update store user data
 - Fixed: Video page attaching multiple event listeners to window causing all sort of issues


## v1.3.6
### Added
 - Added MPI logo to the Login Screen

### Fixed
 - MAJOR FIX: Fixed issue where API was returning 401 and you couldn't access the videos.


## v1.3.5
### Added
 - Added MPI logo in Splash Screen

### Fixed
 - Increased "feedback" size icon
 - Home & Dashboard spacing adjustment


## v1.3.4
### Added
 - Added "Submit feedback" feature for Beta testing
 - Registration form for Individual accounts

### Fixed
 - Removed dummy logins
 - Fixed back to home page on Login page


## v1.3.3
### Added
 - Added "Completed" badge as Component

### Fixed
 - Fixed: Video marked as completed without answering quiz upon finishing watching video
 - Fixed: minor spacing adjusments


## v1.3.0
### Added
 - Added 'completed' badge on videos under "Watch more videos in this section"
 - Added number of videos in a section on Module page
 - Added "You're watching this video offline" on the Offline Video page
 - Added support for video events such as end of video
 - Automatically opens quiz upon finishing watching a video
 - Checks if quiz is available on video, otherwise, it marks it as completed and saves progress
 - Added next video feature
 - Added Loading spinner upon logging in

### Fixed
 - Changed layout on Section and Video page to use VideosRow component
 - Fixed quiz submission: adds ‘completed’ and saves progress
 - Fixed edit icon on profile picture
 

## v1.2.0
### Added
 - Push Notifications: currently only working if triggered manually

### Fixed
 - Android capacitor plugins


## v1.1.0
### Added
 - Added support for Camera
 - Added ability to upload profile picture
 - Added loading spinner on Module & Section pages

### Fixed
 - New page slide animation
 - Fixed Add to Learning for "Employee"
 - Fixed breadcrumbs on Section page
 - Fixed other videos in this section not clickable
 - Changed navigation: profile icon to go to Profile
 - Changed navigation: Menu to go to Account


## v1.0.155
### Added
 - Added "Downloaded" text & icon
 - Added video info on Downloaded Videos page

### Fixed
 - Improved UI on Downloaded Videos page


## v1.0.150
### Added
 - Employer View: Add to Learning
 - Employer View: Team Progress

### Fixed
 

## v1.0.140
### Added
 - Store variables to be saved in Local Storage
 - Added related/recommended for you videos
 - Added User object to Local Storage

### Fixed
 - Increased thumbnail size
 - Added "Download" & "Add to learning" labels
 - Small typography changes
 - Fixed {firstname} missing home page


## v1.0.130
### Added
 - Added "Add to learning" and "Download video" as their own components for easier reuse
 - Added "Continue watching" POST request to API

### Fixed
 - Moved user data to Vuex for easy access accross the app


## v1.0.120
### Added
 - Added Page transition

### Fixed


## v1.0.110
### Added
 - Added API endpoints for module progress and hub subscription

### Fixed
- Module Progress on Learning Page
- Fixed HUB Subscription


## v1.0.109
### Added
 - Added number of sections & videos on Module page
 - Pull module description and show on Module page

### Fixed
- Fixed Videos showing "Section name"


## v1.0.108
### Added
 - Added redownload feature for expired/deleted videos
 - Added icons to show whether a video has been downloaded or is available for download

### Fixed
- Changed layout on Offline Videos page


## v1.0.107
### Added
 - Download feature for all templates that show videos
 - Delete video feature

### Fixed
- Hub Library: changed icons to square 400px
- Increased "assign video" & "download video" icons to md (medium)
- Changed "Assigned to you" under Learning to "Offline Videos"


## v1.0.106
### Added
 - Store user data in Storage upon login
 - Update user data in Storage upon account update

### Fixed
- Read user data from Storage in Home, Dashboard, Profile & Account
