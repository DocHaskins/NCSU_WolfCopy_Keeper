# WolfCopy Keeper - User Guide

**The Complete Printer Fleet Management Solution**

WolfCopy Keeper helps you track supplies, monitor usage, and manage your organization's devices and copiers. Never run out of toner again with smart alerts and usage predictions!

## Getting Started
Youtube Tutorial - https://youtu.be/pDJG-A0HlLo - Getting Started

### Main Navigation
WolfCopy Keeper has four main tabs at the top:
- **🗺️ Map** - See all devices on an interactive map
- **🏢 Buildings** - View devices organized by building
- **🖨️ Devices** - List view of all devices with detailed filtering
- **⚙️ Settings** - Import data, export reports, and configure the app

## Adding Your First Device

### Method 1: Import from Excel (Recommended for Multiple Devices)
1. Go to **Settings** tab → **Import Excel**
2. Select your Excel file with printer data
3. Map the columns (ID, Building, Room, Model, etc.)
4. Preview and confirm the import

### Method 2: Add Individual Devices
1. Go to **Settings** tab → **Add Device**
2. Fill in the required information:
   - **Printer ID** (required)
   - **Model** from the dropdown (required)
   - **Location** (required)
   - **Building** and **Room** (optional but recommended)
3. Add **Network Information** (IP address, MAC address)
4. Set **GPS Location** by clicking "Add GPS Location"
5. Configure **Paper Inventory** if needed
6. Click **Add Printer**

## Managing Locations

### Setting Up Buildings
1. Go to **Settings** tab → **Manage Building Locations**
2. Click the **+** button to add a new location
3. Choose to:
   - **Enter coordinates manually**, or
   - **Select on map** for visual placement
4. Name your building and save

### Location Features
- **Building images**: Customize with photos for easy identification
- **GPS coordinates**: Enable map navigation and directions
- **Import/Export**: Share location data between devices

## Using the Map

### Map Controls (bottom right)
- **+/-** buttons: Zoom in/out
- **📍** button: Go to your current location
- **👁️** button: Toggle your location visibility
- **🏢** button: Toggle building labels
- **⛶** button: Fit all devices on screen

### Map Features
- **Building Directory**: Use the dropdown at the top to jump to specific buildings
- **Status Colors**: 
  - **🟢 Green**: Normal operation
  - **🟡 Orange**: Low paper or warnings
  - **🔴 Red**: Low toner or errors
- **Tap markers**: View printer details or building summary
- **Navigate button**: Get directions to any printer

## Monitoring Supplies

### Toner Levels
- **Circular dials** show percentage remaining for each color
- **Colored rings**: Black, Cyan, Magenta, Yellow
- **Days remaining**: Estimated time until replacement needed
- **Refill button**: Mark toner as replaced when serviced

### Paper Management
- **Box count**: Track paper boxes in inventory
- **Sheets remaining**: Calculate total sheets available
- **Usage tracking**: Monitor consumption patterns
- **Restock alerts**: Get notified when supplies run low

### Supply Status Colors
- **Green (80-100%)**: Plenty remaining
- **Orange (10-79%)**: Order soon
- **Red (0-10%)**: Critical - order immediately

## Filtering and Search

### CSR Filter (top right)
- Filter devices by assigned technician/CSR
- Useful for service routing and accountability

### Buildings Tab Filters
- **Sort by**: Building name, device count, or alert count
- **Filter by status**: All, Alerts, Low Toner, Low Paper
- **Search**: Find buildings by name or room

### Devices Tab Filters
- **Sort by**: Name, location, toner level, paper level, usage, status, model
- **Filter by status**: All, Alerts, Low Toner, Low Paper
- **Search by**: All fields, name, ID, model, or location

## Working with Individual Devices

### Printer Detail Screen
Tap any printer to see:
- **Basic info**: Model, location, specifications
- **Current status**: Online/offline, any error messages
- **Toner levels**: Interactive dials you can adjust
- **Supply management**: Paper and toner tracking
- **Usage statistics**: Printing patterns and trends
- **Notes**: Add maintenance records and observations

### Quick Actions
- **🔄 Refresh**: Update printer status via SNMP (if IP address configured)
- **✏️ Edit**: Modify printer details, location, current levels
- **📍 Navigate**: Get directions to the printer
- **📊 Statistics**: View detailed usage analytics
- **📝 Usage**: Record manual meter readings

## Data Management

### Export Data
**Settings** → **Export to Excel**
- Creates spreadsheet with all printer data
- Includes current supply levels and usage statistics
- Filters by selected CSR if applied

### Backup and Restore
**Settings** → **Export Data Backup**: Create complete data backup
**Settings** → **Import Data Backup**: Restore from backup file

### Excel Import Tips
- **Required columns**: ID, Building, Room, Model
- **Optional columns**: CSR, Department, IP Address, MAC Address, Agreement Type
- **Paper tracking**: Set "Agreement Type" to include "paper" for inventory tracking
- **Multiple files**: Can combine similar Excel files in one import

## Understanding Status Indicators

### Device Status
- **🟢 Normal**: No issues detected
- **🟡 Warning**: Low supplies or minor issues
- **🔴 Error**: Critical supplies or system errors
- **⚫ Offline**: Not responding (powered off or network issue)

### Building View
- **Device count**: Total devices in building
- **Status badges**: Count of devices needing attention
- **Images**: Building photos for easy identification

## Tips for Best Results

### Regular Maintenance
1. **Check supply levels weekly** using the Buildings or Devices tabs
2. **Update toner levels** after replacements via printer detail screens
3. **Record service calls** using the "Record Service" button
4. **Add notes** for maintenance history and special instructions

### Efficient Navigation
- Use **building filter** to focus on specific locations
- Apply **CSR filter** to see only your assigned devices
- **Search function** to quickly find specific devices
- **Map view** for visual location reference

### Data Accuracy
- **Verify GPS coordinates** for accurate map placement
- **Keep building names consistent** across all devices
- **Update room numbers** when devices are moved
- **Record meter readings** for offline devices

## Troubleshooting

### Printer Not Updating
- Verify IP address is correct in printer settings
- Check network connectivity to the printer
- Ensure you're connected to NCSU VPN if working remotely
- Try manual refresh using the 🔄 button

### Location Issues
- Confirm GPS coordinates are entered correctly
- Check that building information matches between devices
- Verify location services are enabled on your device

### Import Problems
- Ensure required columns (ID, Building, Room, Model) are present
- Check for duplicate printer IDs
- Verify building names match existing locations

---