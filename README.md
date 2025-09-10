# AI Project: PlantPal – AI Reminder to Water Your Plants

## Summary
PlantPal is a simple AI assistant that reminds users when to water their plants based on plant type and local weather conditions. It helps prevent overwatering or underwatering by sending smart, timely notifications.

## Background
Keeping houseplants alive can be surprisingly tricky. Different plants have different watering needs, and weather conditions like humidity and rainfall affect how often they should be watered. Many people either forget to water or do it too often, leading to unhappy plants. PlantPal solves this by combining plant care knowledge with weather data to give personalized watering reminders.

## How is it used?
Users input:
- The type of plant (e.g., cactus, fern, peace lily)
- Their location (for weather tracking)

The AI checks the weather forecast and sends reminders when watering is needed. It can also suggest skipping watering if it's been rainy or humid. Over time, it learns from user feedback (e.g., “my plant still looks dry”) to improve its recommendations.

## Data and AI techniques
- **Data sources**:
  - Public plant care databases
  - Weather APIs (e.g., OpenWeatherMap)
- **AI techniques**:
  - Rule-based logic for basic plant needs
  - Simple machine learning to adapt reminders based on user feedback
  - Optional: Natural Language Processing (NLP) for interpreting user comments

## Challenges
- Limited data for rare or exotic plants
- Users may ignore reminders or forget to give feedback
- Without sensors, it's hard to measure actual soil moisture
- Privacy concerns if location data is stored

## What next?
Future versions could:
- Integrate with smart home devices or soil moisture sensors
- Use image recognition to assess plant health from photos
- Include voice assistant support for hands-free interaction
- Build a community feature for sharing plant care tips

## Acknowledgments
Inspired by the everyday challenge of keeping houseplants alive and the potential of combining weather data with AI. Thanks to open-source plant databases and weather APIs that make this idea possible.
