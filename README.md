# Panchtatva Shudh Ahaar × Shudh Annapurna: test site (final merged version)

## Upload these to GitHub (same level, in the repository root)
- `index.html`
- the `images` folder (with its `menu` and `gallery` sub-folders)
- `README.md` (optional)

Then: Settings > Pages > Deploy from a branch > `main` / root > Save. Your address appears after about a minute.
`index.html` carries its own copy of the brand images, so the logos show even if the `images` folder is missed.

## How the site is segmented (one short page at a time)
| Nav item | Shows |
|---|---|
| Home | Roots hook, "Where to next?" photo doors, Photos + Our roots side by side, Find us |
| Shudh Annapurna | Tabs: Ways to eat / Menu / Order direct |
| Panchtatva Catering | Tabs: Services / Why Panchtatva / How it works / FAQ / Get a quote (with call card) |
| Our Roots | Story timeline and poster |
| Photos | Facebook / Instagram / your own photos |
| Find Us | Google Maps, two places |

Fonts: Cinzel (labels), Cormorant Garamond (headings), DM Sans (text). Palette: maroon, gold, ivory.

## Settings (top of the script in `index.html`)
| Setting | Now | Meaning |
|---|---|---|
| `TEST_MODE` | `true` | Enquiries and direct orders open WhatsApp to the test number. Set `false` to use the real numbers (`waCorp`, `waRest`). |
| `SHOW_DRAFTS` | `true` | Shows unconfirmed dishes and story items, labelled "Draft". Set `false` for the live site. |
| `links` | Swiggy, Zomato, Instagram, Facebook | Confirm the Swiggy/Zomato addresses are the right listings. |
| `places` | restaurant and business address | Drive the Google Maps tabs, directions and copy-address buttons. |
| `WEB` | dish to Wikimedia Commons photo | Stand-in photos, tagged "Representative photo" and credited in the footer. |
| `FEATURED` | 8 dishes | Which dishes show before "Show all". |

## Photos
- Real dish photos: `images/menu/<dish-name>.jpg` (names in `images/menu/README.txt`). A real photo replaces the stand-in automatically.
- Your own gallery: `images/gallery/g1.jpg` ... `g12.jpg`.
- Stand-in web photos are not photos of your food. Remove the `WEB` entries once you have your own.

## Needs the owner
Prices, descriptions and photos for every dish; the founding year (the poster logo says "since 23 years", IndiaMART says 1999, another listing says 1997); real WhatsApp numbers; Swiggy/Zomato links; confirmation of "Pure vegetarian", "Over two decades ago a family kitchen opened…" and the "How it works" steps.
