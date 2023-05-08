# Synergetic Media Elementor Icon Box Custom Code

Icon Box widget CSS for Elementor

## Getting Started

1. Create a container.
   Edit Container
   |**Layout
   |**Container
   |**Boxed => Width 1140px
   |**Items
   |\_\_Direction => Row

2. Create 6 containers inside it.
   Edit Container
   |**Layout
   |**Container
   |**content width => Full width
   |**Width: 25%,
   |**Items
   |**Direction => Column
   |**Align Items => Center
   |**Gap between elements => 0
   |**Advanced
   |**Margin => 0px 0px 25px 0px
   |**Padding 15px 0px 0px 0px
   |**CSS Classes => icon-box uniqueprefix_icon_box. For SYM I used icon-box commercial_icon_box, icon-box grapic_icon_box etc.

3. Add image widget. Note: all images chosen must have 1:1 aspect ratio. The animation image is 40px too tall so the fix is to give it a width of 34% on desktop and tablet. Then 44% for mobile.
   Edit Image
   |**Image
   |**Image Size => thumbnail 300x300.
   |**Style
   |**Image
   |**Width: 40%.
   |**Advanced
   |**Layout
   |**Margin => 0px 0px 25px 0px
   |\_\_Padding 5px 0px 0px 0px.

4. Add heading widget.
   Edit Heading
   |**Content
   |**Title
   |**HTML Tag => H4
   |**Alignment => Center
   |**Style
   |**set ur styles!
   |**Advanced
   |**CSS Classes => title

5. Paste SYM_icon-box-styles.css code into Wordpress customizer or Elementor custom code area.

## Author

Charles Loehle
@charles-loehle

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## License

GNU GENERAL PUBLIC LICENSE
