ttk_add_vtk_library(ttkContourForests
	SOURCES ttkContourForests.cpp
	HEADERS ttkContourForests.h
	LINK geometry contourForests contourForestsTree ttkTriangulation)
