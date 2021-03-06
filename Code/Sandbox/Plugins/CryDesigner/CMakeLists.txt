#START-FILE-LIST
# File List auto generated by waf2cmake.py, do not modify manually.

start_sources()
# -- crydesigner.waf_files --
sources_platform(ALL)
add_sources("CryDesigner_Basic.cpp"
	SOURCE_GROUP "Objects"
		"Objects/DesignerBaseObject.h"
		"Objects/DesignerBaseObject_Impl.h"
		"Objects/DesignerObject.h"
		"Objects/DesignerObject.cpp"
		"Objects/AreaSolidObject.h"
		"Objects/AreaSolidObject.cpp"
		"Objects/ClipVolumeObject.h"
		"Objects/ClipVolumeObject.cpp"
	SOURCE_GROUP "Scripts"
		"Scripts/BasicScripts.cpp"
		"Scripts/BasicScripts.h"
		"Scripts/ShapeScripts.cpp"
		"Scripts/EditScripts.cpp"
		"Scripts/ModifyScripts.cpp"
		"Scripts/SelectionScripts.cpp"
)

add_sources("CryDesigner_Core.cpp"
	SOURCE_GROUP "Core"
		"Core/ModelCompiler.cpp"
		"Core/ModelCompiler.h"
		"Core/BSPTree2D.cpp"
		"Core/BSPTree2D.h"
		"Core/BSPTree3D.cpp"
		"Core/BSPTree3D.h"
		"Core/Helper.cpp"
		"Core/Helper.h"
		"Core/Convexes.h"
		"Core/Declaration.h"
		"Core/Model.cpp"
		"Core/Model.h"
		"Core/Boolean3D.cpp"
		"Core/ModelDB.cpp"
		"Core/ModelDB.h"
		"Core/HalfEdgeMesh.cpp"
		"Core/HalfEdgeMesh.h"
		"Core/PolygonDecomposer.cpp"
		"Core/PolygonDecomposer.h"
		"Core/Line.h"
		"Core/Plane.h"
		"Core/Polygon.cpp"
		"Core/Polygon.h"
		"Core/LoopPolygons.cpp"
		"Core/LoopPolygons.h"
		"Core/PolygonMesh.cpp"
		"Core/PolygonMesh.h"
		"Core/Subdivision.cpp"
		"Core/Subdivision.h"
		"Core/FlexibleMesh.h"
		"Core/FlexibleMesh.cpp"
		"Core/Common.cpp"
		"Core/Common.h"
		"Core/SmoothingGroup.cpp"
		"Core/SmoothingGroup.h"
		"Core/SmoothingGroupManager.cpp"
		"Core/SmoothingGroupManager.h"
		"Core/UVIsland.h"
		"Core/UVIsland.cpp"
		"Core/UVIslandManager.h"
		"Core/UVIslandManager.cpp"
		"Core/EdgesSharpnessManager.h"
		"Core/EdgesSharpnessManager.cpp"
)

add_sources("CryDesigner_Tool.cpp"
	SOURCE_GROUP "Tools"
		"Tools/AreaSolidTool.cpp"
		"Tools/AreaSolidTool.h"
		"Tools/ClipVolumeTool.h"
		"Tools/ClipVolumeTool.cpp"
		"Tools/BaseTool.cpp"
		"Tools/BaseTool.h"
		"Tools/ToolCommon.h"
		"Tools/ToolCommon.cpp"
)

add_sources("CryDesigner_Tool_Edit.cpp"
	SOURCE_GROUP "Tools\\\\Edit"
		"Tools/Edit/ExtrudeTool.cpp"
		"Tools/Edit/ExtrudeTool.h"
		"Tools/Edit/ExtrudeMultipleTool.cpp"
		"Tools/Edit/ExtrudeMultipleTool.h"
		"Tools/Edit/ExtrudeEdgeTool.cpp"
		"Tools/Edit/ExtrudeEdgeTool.h"
		"Tools/Edit/FillTool.cpp"
		"Tools/Edit/FillTool.h"
		"Tools/Edit/FlipTool.cpp"
		"Tools/Edit/FlipTool.h"
		"Tools/Edit/MergeTool.cpp"
		"Tools/Edit/MergeTool.h"
		"Tools/Edit/OffsetTool.cpp"
		"Tools/Edit/OffsetTool.h"
		"Tools/Edit/RemoveDoublesTool.cpp"
		"Tools/Edit/RemoveDoublesTool.h"
		"Tools/Edit/RemoveTool.cpp"
		"Tools/Edit/RemoveTool.h"
		"Tools/Edit/CopyTool.cpp"
		"Tools/Edit/CopyTool.h"
		"Tools/Edit/WeldTool.cpp"
		"Tools/Edit/WeldTool.h"
		"Tools/Edit/CollapseTool.h"
		"Tools/Edit/CollapseTool.cpp"
		"Tools/Edit/SeparateTool.cpp"
		"Tools/Edit/SeparateTool.h"
)

add_sources("CryDesigner_Tool_Misc.cpp"
	SOURCE_GROUP "Tools\\\\Misc"
		"Tools/Misc/Pivot2BottomTool.cpp"
		"Tools/Misc/Pivot2BottomTool.h"
		"Tools/Misc/SnapToGridTool.cpp"
		"Tools/Misc/SnapToGridTool.h"
		"Tools/Misc/HidePolygonTool.cpp"
		"Tools/Misc/HidePolygonTool.h"
		"Tools/Misc/ResetXFormTool.cpp"
		"Tools/Misc/ResetXFormTool.h"
		"Tools/Misc/ExportTool.cpp"
		"Tools/Misc/ExportTool.h"
)

add_sources("CryDesigner_Tool_Modify.cpp"
	SOURCE_GROUP "Tools\\\\Modify"
		"Tools/Modify/LoopCutTool.cpp"
		"Tools/Modify/LoopCutTool.h"
		"Tools/Modify/BevelTool.cpp"
		"Tools/Modify/BevelTool.h"
		"Tools/Modify/BooleanTool.cpp"
		"Tools/Modify/BooleanTool.h"
		"Tools/Modify/CloneTool.cpp"
		"Tools/Modify/CloneTool.h"
		"Tools/Modify/LatheTool.cpp"
		"Tools/Modify/LatheTool.h"
		"Tools/Modify/MagnetTool.cpp"
		"Tools/Modify/MagnetTool.h"
		"Tools/Modify/MirrorTool.cpp"
		"Tools/Modify/MirrorTool.h"
		"Tools/Modify/SliceTool.cpp"
		"Tools/Modify/SliceTool.h"
		"Tools/Modify/SubdivisionTool.cpp"
		"Tools/Modify/SubdivisionTool.h"
)

add_sources("CryDesigner_Tool_Select.cpp"
	SOURCE_GROUP "Tools\\\\Select"
		"Tools/Select/InvertSelectionTool.cpp"
		"Tools/Select/InvertSelectionTool.h"
		"Tools/Select/LoopSelectionTool.cpp"
		"Tools/Select/LoopSelectionTool.h"
		"Tools/Select/RingSelectionTool.cpp"
		"Tools/Select/RingSelectionTool.h"
		"Tools/Select/SelectAllNoneTool.cpp"
		"Tools/Select/SelectAllNoneTool.h"
		"Tools/Select/SelectConnectedTool.cpp"
		"Tools/Select/SelectConnectedTool.h"
		"Tools/Select/SelectGrowTool.cpp"
		"Tools/Select/SelectGrowTool.h"
		"Tools/Select/SelectTool.cpp"
		"Tools/Select/SelectTool.h"
		"Tools/Select/MovePipeline.cpp"
		"Tools/Select/MovePipeline.h"
		"Tools/Select/MoveTool.cpp"
		"Tools/Select/MoveTool.h"
		"Tools/Select/PivotTool.cpp"
		"Tools/Select/PivotTool.h"
)

add_sources("CryDesigner_Tool_Shape.cpp"
	SOURCE_GROUP "Tools\\\\Shape"
		"Tools/Shape/BoxTool.cpp"
		"Tools/Shape/BoxTool.h"
		"Tools/Shape/ConeTool.cpp"
		"Tools/Shape/ConeTool.h"
		"Tools/Shape/CylinderTool.cpp"
		"Tools/Shape/CylinderTool.h"
		"Tools/Shape/SphereTool.cpp"
		"Tools/Shape/SphereTool.h"
		"Tools/Shape/CubeEditor.cpp"
		"Tools/Shape/CubeEditor.h"
		"Tools/Shape/CurveTool.cpp"
		"Tools/Shape/CurveTool.h"
		"Tools/Shape/DiscTool.cpp"
		"Tools/Shape/DiscTool.h"
		"Tools/Shape/PolylineTool.cpp"
		"Tools/Shape/PolylineTool.h"
		"Tools/Shape/RectangleTool.cpp"
		"Tools/Shape/RectangleTool.h"
		"Tools/Shape/ShapeTool.cpp"
		"Tools/Shape/ShapeTool.h"
		"Tools/Shape/StairProfileTool.cpp"
		"Tools/Shape/StairProfileTool.h"
		"Tools/Shape/StairTool.cpp"
		"Tools/Shape/StairTool.h"
)

add_sources("CryDesigner_Tool_Surface.cpp"
	SOURCE_GROUP "Tools\\\\Surface"
		"Tools/Surface/SmoothingGroupTool.cpp"
		"Tools/Surface/SmoothingGroupTool.h"
		"Tools/Surface/UVMappingTool.cpp"
		"Tools/Surface/UVMappingTool.h"
	SOURCE_GROUP "UVMappingEditor"
		"UVMappingEditor/UVMappingEditorCommon.cpp"
		"UVMappingEditor/UVMappingEditorCommon.h"
		"UVMappingEditor/UVMappingEditor.cpp"
		"UVMappingEditor/UVMappingEditor.h"
		"UVMappingEditor/UVElement.cpp"
		"UVMappingEditor/UVElement.h"
		"UVMappingEditor/UVCursor.cpp"
		"UVMappingEditor/UVCursor.h"
		"UVMappingEditor/UVGizmo.cpp"
		"UVMappingEditor/UVGizmo.h"
		"UVMappingEditor/UVCluster.cpp"
		"UVMappingEditor/UVCluster.h"
		"UVMappingEditor/UVUndo.cpp"
		"UVMappingEditor/UVUndo.h"
		"UVMappingEditor/BaseTool.cpp"
		"UVMappingEditor/BaseTool.h"
	SOURCE_GROUP "UVMappingEditor\\\\ManipulationTools"
		"UVMappingEditor/ManipulationTools/SelectTool.cpp"
		"UVMappingEditor/ManipulationTools/SelectTool.h"
		"UVMappingEditor/ManipulationTools/MoveTool.cpp"
		"UVMappingEditor/ManipulationTools/MoveTool.h"
		"UVMappingEditor/ManipulationTools/AlignTool.cpp"
		"UVMappingEditor/ManipulationTools/AlignTool.h"
		"UVMappingEditor/ManipulationTools/SewTool.cpp"
		"UVMappingEditor/ManipulationTools/SewTool.h"
		"UVMappingEditor/ManipulationTools/UnmapTool.cpp"
		"UVMappingEditor/ManipulationTools/UnmapTool.h"
		"UVMappingEditor/ManipulationTools/SeparateTool.cpp"
		"UVMappingEditor/ManipulationTools/SeparateTool.h"
		"UVMappingEditor/ManipulationTools/FlipTool.cpp"
		"UVMappingEditor/ManipulationTools/FlipTool.h"
		"UVMappingEditor/ManipulationTools/SelectSharedTool.cpp"
		"UVMappingEditor/ManipulationTools/SelectSharedTool.h"
		"UVMappingEditor/ManipulationTools/LoopSelectionTool.cpp"
		"UVMappingEditor/ManipulationTools/LoopSelectionTool.h"
	SOURCE_GROUP "UVMappingEditor\\\\UnwrappingTools"
		"UVMappingEditor/UnwrappingTools/PlaneUnwrappingTool.cpp"
		"UVMappingEditor/UnwrappingTools/PlaneUnwrappingTool.h"
		"UVMappingEditor/UnwrappingTools/CubeUnwrappingTool.cpp"
		"UVMappingEditor/UnwrappingTools/CubeUnwrappingTool.h"
		"UVMappingEditor/UnwrappingTools/CylinderUnwrappingTool.cpp"
		"UVMappingEditor/UnwrappingTools/CylinderUnwrappingTool.h"
		"UVMappingEditor/UnwrappingTools/ViewUnwrappingTool.cpp"
		"UVMappingEditor/UnwrappingTools/ViewUnwrappingTool.h"
		"UVMappingEditor/UnwrappingTools/SphereUnwrappingTool.cpp"
		"UVMappingEditor/UnwrappingTools/SphereUnwrappingTool.h"
)

add_sources("CryDesigner_UIs.cpp"
	SOURCE_GROUP "UIs"
		"UIs/DesignerDockable.cpp"
		"UIs/DesignerDockable.h"
		"UIs/DesignerPanel.cpp"
		"UIs/DesignerPanel.h"
		"UIs/DesignerSubPanel.h"
		"UIs/DesignerSubPanel.cpp"
		"UIs/CubeEditorPanel.cpp"
		"UIs/CubeEditorPanel.h"
		"UIs/SubdivisionPanel.cpp"
		"UIs/SubdivisionPanel.h"
		"UIs/SmoothingGroupPanel.h"
		"UIs/SmoothingGroupPanel.cpp"
		"UIs/PropertyTreePanel.h"
		"UIs/UICommon.cpp"
		"UIs/UICommon.h"
)

add_sources("CryDesigner_Util.cpp"
	SOURCE_GROUP "Util"
		"Util/ElementSet.cpp"
		"Util/ElementSet.h"
		"Util/ExtrusionSnappingHelper.cpp"
		"Util/ExtrusionSnappingHelper.h"
		"Util/DesignerSettings.cpp"
		"Util/DesignerSettings.h"
		"Util/Converter.cpp"
		"Util/Converter.h"
		"Util/PrimitiveShape.cpp"
		"Util/PrimitiveShape.h"
		"Util/SpotManager.cpp"
		"Util/SpotManager.h"
		"Util/Undo.cpp"
		"Util/Undo.h"
		"Util/Exporter.cpp"
		"Util/Exporter.h"
		"Util/HeightManipulator.cpp"
		"Util/HeightManipulator.h"
		"Util/OffsetManipulator.cpp"
		"Util/OffsetManipulator.h"
		"Util/ArgumentModel.cpp"
		"Util/ArgumentModel.h"
		"Util/UVUnwrapUtil.h"
		"Util/UVUnwrapUtil.cpp"
		"Util/Display.h"
		"Util/Display.cpp"
		"Util/ExcludedEdgeManager.h"
		"Util/ExcludedEdgeManager.cpp"
)

add_sources("NoUberFile"
	SOURCE_GROUP "Root"
		"StdAfx.h"
		"StdAfx.cpp"
		"Resource.h"
		"main.cpp"
		"CryDesigner.rc"
		"ToolFactory.h"
		"DesignerEditor.cpp"
		"DesignerEditor.h"
		"DesignerSession.cpp"
		"DesignerSession.h"
)

end_sources()
#END-FILE-LIST

CryEditorPlugin(CryDesigner PCH "StdAfx.cpp" SOLUTION_FOLDER "Sandbox/Plugins")
target_include_directories(${THIS_PROJECT} PRIVATE .. "${CRY_EXTENSIONS_DIR}/CryLink/Interface")
target_include_directories(${THIS_PROJECT} PRIVATE ../../EditorQt)	
target_include_directories(${THIS_PROJECT} PRIVATE ../../EditorQt/Include)
target_include_directories(${THIS_PROJECT} PRIVATE ../MFCToolsPlugin)

target_link_libraries(${THIS_PROJECT} PRIVATE Sandbox)
target_link_libraries(${THIS_PROJECT} PRIVATE MFCToolsPlugin)

use_xt()

