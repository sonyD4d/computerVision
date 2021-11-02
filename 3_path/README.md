# Airport Distance Using Path

        - Calculate the distance between indian airports by using path 
        - Path calculated using Euclidean distance
        - Assuming 4,d and 8 connected
     
# Connectivity between pixels

![1_gFh1mfAZKixmgIQQudj4Sg](https://user-images.githubusercontent.com/20265851/139598091-0e767948-2422-4180-b2d8-6cd1c609fc6f.png)

    Two pixels are said to be connected:
      - if they are adjacent in some sense(neighbour pixels,4/8/m-adjacency)
      - if their gray levels satisfy a specified criterion of similarity(equal intensity level)
      
    There are three types of connectivity on the basis of adjacency. They are:
      a) 4-connectivity: Two or more pixels are said to be 4-connected if they are 4-adjacent with each others.
      b) 8-connectivity: Two or more pixels are said to be 8-connected if they are 8-adjacent with each others.
      c) m-connectivity: Two or more pixels are said to be m-connected if they are m-adjacent with each others.

# Path

    A path from pixel p with coordinates (x, y) to pixel q with coordinates (s, t) is a sequence of distinct pixels with coordinates:
      (x0, y0), (x1, y1), (x2, y2) … (xn, yn),where (x0, y0)=(x, y) and (xn, yn)=(s, t);
      (xi, yi) is adjacent to (xi-1, yi-1)
