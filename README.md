# refugee-resources

Canonical Chicago-area (and expanding multi-state) resource listings for Aidr.

## Resource layout

Listings live under **`resources/{STATE}/`** (USPS state code):

- `resources/IL/healthcare.txt`
- `resources/IL/education.txt`
- `resources/IL/ResettlementLegalShelterBasicNeeds.txt`
- `resources/CO/…`, `resources/CA/…`, …

Aidr agents import HRSA Health Center Excel into `healthcare.txt` per state (hub city + 250-mile filter), then refresh local JSON after approve/apply.
