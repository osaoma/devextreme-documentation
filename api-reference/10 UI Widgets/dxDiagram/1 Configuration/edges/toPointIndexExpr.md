---
id: dxDiagram.Options.edges.toPointIndexExpr
type: String | function(data)
default: undefined
---
---
##### shortDescription
Specifies the name of a data source field or an expression that provides an index of a shape connection point where an edge ends.

##### param(data): Object
The current edge's data object.

---
The built-in shape's connection points are numbered clockwise from the leftmost point on the top border.

![Diagram - Shape Points](/images/diagram/point-index-expr.png)

A custom shape's connection points are numbered according to their position in the [connectionPoints](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/customShapes/connectionPoints/) collection.