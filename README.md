1. Create a function named procedure Depth_First
2. if not visited[i] then visited[i] := true; with Tree traversals.
3. for all edge <i,j> Depth_First(j) , j must follow i in top'-sort
4. end for; save(i), record or process Vertex i
5. end Depth_First;
6. for all i :Vertex visited[i] := false ,initialise visited[]; been nowhere!
7. end for; for all i :Vertex Depth_First(i) ,try all possible starting points
8. end for Depth-First Traversal of a Graph from a given Vertex.
