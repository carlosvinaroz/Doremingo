# Doremingo

A native macOS app for weekly meal planning and automatic shopping list generation. Built with SwiftUI and SwiftData.

## Features

### Recipe Management
- Create, edit, and delete recipes with name, description, servings, prep time, category, and tags
- Automatic nutritional breakdown (kcal, protein, carbs, fat) per recipe and per serving
- Cost per recipe and per serving based on ingredient prices
- Filter recipes by category (Breakfast, Lunch, Dinner, Batch Cooking)
- Tag system: Quick, Healthy, Freezable, Tupperware, Vegetarian, Cheap

### Food Database
- Dashboard organized by 17 Spanish supermarket categories with icons
- Store nutritional values per 100g (kcal, protein, carbs, fat)
- Price per kg for cost estimation
- Default units and shopping categories per food
- Inline editing in detail pane
- Sample data with 19 common foods

### Weekly Planner
- Drag-and-drop style grid: 7 days × 3 meals (Breakfast, Lunch, Dinner)
- Today's row highlighted automatically
- Per-person scaling based on number of people setting
- Daily nutritional summary per person with averages
- Weekly cost breakdown
- **Save & load plans** — save your favorite weekly plans and reload them anytime

### Shopping List
- Auto-generated from the weekly plan
- Ingredients aggregated by shopping category
- Checkbox to mark items as purchased with progress bar
- Share to Apple Notes, Mail, Messages, AirDrop (native macOS share sheet)
- Copy to clipboard
- Exported as a checklist format (☐) organized by category

### Settings
- Number of people (scales recipes and shopping list)
- Load sample data
- Clear weekly plan
- Delete all data
- Statistics overview

## Tech Stack

- **SwiftUI** — declarative UI with NavigationSplitView
- **SwiftData** — persistence with @Model, @Query, @Relationship
- **macOS 14+** — native macOS app
- **No dependencies** — pure Apple frameworks

## Architecture
