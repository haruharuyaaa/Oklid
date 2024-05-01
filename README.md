import math
points = [(4, 11), (4, 14)]
def euclideanDistance(point1, point2):
  return math.sqrt((point2[0]) ** 2 +(point2[1] - point1[1]) ** 2)
  distanes = []
for i in range(len(points)):
  for j in range(i + 1, len(points)):
    distances.append(euclideanDistance(points[1], points[j]))
print(min(distances))
3
