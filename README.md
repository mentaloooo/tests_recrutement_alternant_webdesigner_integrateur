# product_page_description_integration

## Guidelines

### HTML

- Each description block need to be inside a `section` node
- Accent need to be html encoded to avoid encoding issues

### CSS

- Native css (no lib/framework/tools like bootstrap, tailwind, ...)
- CSS need to be compatible with existing styles
- CSS need to be wrote inside a stand alone file (with factored syles between all products pages)
- CSS need to implement vendor prefixes for compatibility purpose

### Javascript

- Native Javascript (no lib/framework/tools like JQuery, React, ...)
- Javascript need to be browser friendly (no esx or typescript)

---

## How to use

A list of placeholder sections is prefill inside the `isolated_stores-discount_product_page.html` file at line **8776**

This section list look like:

```html
<div class="dynamicContent">
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- Espace d'integration -->
  <section id="presentation" class="s-presentation detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <h2>Placeholder</h2><br/>
    <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris plaeleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enturpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna ererat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus<br/><br/><br/><br/><br/><br/><br><br/></p>
    <!--  -->
  </section>
  
  <section id="matieres" class="detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <h2>Placeholder</h2><br/>
    <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris plaeleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enturpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna ererat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus<br/><br/><br/><br/><br/><br/><br><br/></p>
    <!--  -->
  </section>
  
  <section id="coffre" class="detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <h2>Placeholder</h2><br/>
    <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris plaeleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enturpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna ererat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus<br/><br/><br/><br/><br/><br/><br><br/></p>
    <!--  -->
  </section>
  
  <section id="commande" class="detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <h2>Placeholder</h2><br/>
    <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris plaeleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enturpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna ererat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus<br/><br/><br/><br/><br/><br/><br><br/></p>
    <!--  -->
  </section>
  
  <section id="pose" class="detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <h2>Placeholder</h2><br/>
    <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris plaeleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enturpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna ererat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus<br/><br/><br/><br/><br/><br/><br><br/></p>
    <!--  -->
  </section>
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
  <!-- ************************************************ -->
</div>
```

Each block need to be inside a `section` node with a `detailsSection` class

```html
<section id="blockId" class="detailsSection">
    <!--  -->
    <!-- Content block placeholder -->
    <!--  -->
  </section>
```

> `id="blockId"` refer to the navbar integration `fp-sticky-nav` at line 8761

