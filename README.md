BlenderSciViz
=============

Preliminary code for plotting data in Blender.

###What this project hopes to achieve?  
Create analogues for common plotting needs in the scientific and data community. Provide sufficiently readable 
examples as a foundation for maximum customization by those willing to learn.

###Useful code snippets and addons

**scatter plots**
- 1d array to point cloud, takes array of {x,y,z} tuples and generates vertices
- 1d array to point cloud, takes array of {x,y,z,c} tuples and generates colored dots (renderable geometry)

**mesh plot**
- 2d array to 3d mesh, takes n*n array of {x,y,z} tuples and generates a mesh
- Automatic colour map for 3d mesh data

###Todo

    plt.{x,y,z}label,   
    plt.gca, 
    plt.plot(cos(x in range(0,2*pi, 0.01*pi)) ),