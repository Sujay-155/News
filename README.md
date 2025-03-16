Political Pulse
A location-aware political news aggregator that delivers personalized news content from global to local levels.

Features
Location-Based News: Automatically detects user location and shows relevant political news
Multi-Level Coverage: Displays news at global, country, state, and local levels
Search Functionality: Find specific political topics across all geographical levels
Category Filtering: Toggle between different location categories
Search History: Tracks and displays user search patterns
Responsive Design: Works on both desktop and mobile devices
Fallback Systems: Multiple backup methods for location detection and news sources

How It Works
Political Pulse uses browser geolocation to determine your location, then fetches relevant political news using multiple news APIs. If geolocation isn't available, it falls back to IP-based location detection or uses a default location.

Key Components
Location Services
Browser Geolocation API with permission handling
OpenStreetMap reverse geocoding
IP-based fallback with ipapi.co
News Retrieval
Primary source: NewsAPI.org for all categories
Secondary source: GNews API for redundancy
Location-specific queries for relevant results
User Preferences
Search history tracking
Search frequency analysis
Local storage for persistence between sessions
Search decay algorithm for relevance
User Interface
Category-based navigation
Modal for viewing search patterns
Responsive grid layout
Loading states and error handling
API Usage Notes
The application uses free API keys with limited quotas:

NewsAPI.org: Limited to 100 requests per day
GNews API: Limited to 100 requests per day
These limitations mean the application may stop retrieving new content after reaching daily limits.


Future Improvements
User accounts for preferences across devices
Email alerts for specific political topics
Dark mode toggle
Additional news sources
Social sharing integration
