############################################################################
# CMakeLists.txt file for building ROOT gui/webgui6 package
############################################################################

ROOT_STANDARD_LIBRARY_PACKAGE(WebGui6
  HEADERS
    TWebCanvas.h
    TWebGuiFactory.h
    TWebMenuItem.h
    TWebPadPainter.h
    TWebPainting.h
    TWebSnapshot.h
  SOURCES
    src/TWebCanvas.cxx
    src/TWebGuiFactory.cxx
    src/TWebMenuItem.cxx
    src/TWebPadPainter.cxx
    src/TWebPainting.cxx
    src/TWebSnapshot.cxx
  LIBRARIES
    Core
    Gui 
    ROOTWebDisplay
)
