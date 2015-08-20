Для дальнейшей разработки:

1. bower install
2. в файле bootstrap.scss подключены только:
  
  // Core variables and mixins
  @import "bootstrap/variables";
    // изменены пути к иконкам glyphicons
    
  @import "bootstrap/mixins";
  
  // Reset and dependencies
  @import "bootstrap/normalize";
  @import "bootstrap/glyphicons";
  
  // Core CSS
  @import "bootstrap/scaffolding";
  @import "bootstrap/grid";
  
  // Components w/ JavaScript
  @import "bootstrap/carousel";
  
  // Utility classes
  @import "bootstrap/utilities";
  @import "bootstrap/responsive-utilities";
