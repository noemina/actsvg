# Set up the core tests.
actsvg_add_test( core
  "arc.cpp"
  "arrows.cpp"
  "barrel.cpp" 
  "bezier.cpp"
  "circle.cpp"
  "copy.cpp"
  "endcap.cpp"
  "grids.cpp"
  "infobox.cpp"
  "line.cpp"
  "markers.cpp"
  "measures.cpp"
  "polygon.cpp"
  "rectangle.cpp"
  "style.cpp"
  "svg.cpp"
  "text.cpp"
  "views.cpp"
LINK_LIBRARIES GTest::gtest_main actsvg::core actsvg::data)