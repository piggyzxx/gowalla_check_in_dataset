# temporal_activity_motifs_dataset
This is the Gowalla check-in dataset used in our paper "Discovering activity transition patterns in check-in data through temporal activity motifs".

File Gowalla_checkins_New York-Newark-Jersey City, NY-NJ-PA.csv (unzipped from the zip file with the same name) contains check-ins with 6 columns, which are:

  1. userid (anonymized)
  2. placeid (ID of check-in POI)
  3. datetime (local time)
  4. lat (latitude of check-in POI)
  5. lng (longitude of check-in POI)
  6. spot_categories (detailed category of check-in POI)

File gowalla_category_structure.json contains the original multi-level classification system provided by the gowalla website.

File gowalla_categories_readjusted.json contains the manually adjusted classification system which can reflect users' activity types and is used in our paper.
