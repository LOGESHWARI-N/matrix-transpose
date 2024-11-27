# matrix-transpose
matrix = [[2, 4, 6],
          [1, 3, 5],
          [11, 20 , 15]]

rows, cols = len(matrix), len(matrix[0])
transpose_matrix = [[0 for _ in range(rows)] for _ in range(cols)]

for i in range(rows):
    for j in range(cols):
        transpose_matrix[j][i] = matrix[i][j]

print("Transposed Matrix:")
for row in transpose_matrix:
    print(row)
