# VOX Musical Theatre Inventory System

The new VOX inventory will use google sheets as a database and a website run by google app scripts to edit and view the data. By using google sheets as the database it allows the data to still be editable in the event that the web app stops working, it also means we don’t need to run or pay for a server. 

This will initially be only for scenic supplies (tools, furniture, lumber, etc.), if it works well then we can phase in lighting, sound, props, costume, etc. Costumes would possibly need a different database structure and sorting system

This system will be accompanied by detailed documentation so it can be fixed in the future when it inevitably breaks.

**Desired Features** (I know this looks like a lot, but it is not much more than what is in our current spreadsheet system)
- Data fields for items:
  - Required
  - Category
    - Should be able to list multiple per item
  - Name
  - Quantity
  - Location
  - Date updated including person(s)
- Optional
  - Sub category
  - Sub location
    - Totes, toolboxes, etc
  - Description
  - Notes
  - Condition
  - Manufacture
  - Picture
    - It may be difficult to display in the site, may just be a GDrive link
  - Serial Number
  - Asset tag #
  - Purchase date

- Separate pages for:
  - Viewing equipment
    - Ability to sort by any category or search by text
    - Edit entries
    - Add new entries
  - Equipment check out
  - Equipment check in
  
- Ability to check out/in whole totes

**Future Features:** (never gonna happen but i can still dream)
- Load in list creation
- Alert TD when condition marked as “broken”
- Barcode reading for asset tags

