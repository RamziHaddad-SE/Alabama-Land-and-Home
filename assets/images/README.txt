Drop real photos here, then wire them into the pages (see ../../README.md).

Recommended shots for Alabama Land & Home:
  hero.jpg            wide South-Alabama land or a country home
  glen.jpg            a real photo of Glen Powell / the team (owner section + about)
  land.jpg            acreage / hunting land / timber
  home.jpg            a country home
  farm.jpg            a farm with pasture / barn
  florala.jpg, andalusia.jpg, defuniak.jpg ...  area photos (community cards)
  property-1..6.jpg   real listing photos for property cards

How to wire them in:
  - Hero: background-image on .hero__img
  - Owner: .owner__photo ; About feature: .feature__media
  - Property cards: replace each .property__media p-1..p-6 class with
      style="background-image:url('assets/images/property-1.jpg')"
  - Land badge stays on land listings (.property__badge--land)

Better still: connect a real MLS/land-listing feed so inventory stays current.
Tips: landscape orientation, ~1600px wide, compressed (JPG/WebP).
