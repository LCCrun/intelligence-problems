# <center>Intelligence Problems</center>

intelligence problems for interviews.

### 水壶倒水

1. 无穷多的水
2. 5L 容器和 6L 容器

<details> <summary> 如何得到 3L 水？ </summary>

1. 倒满 6L 容器，然后全部倒到 5L 容器，6L 容器剩余 1L，5L 容器的水全部倒掉，将 6L 容器的 1L 倒到 5L 容器
    - 6L 容器: 0L
    - 5L 容器: 2L
2. 倒满 6L 容器，然后全部倒到 5L 容器，6L 容器剩余 2L（因为 5L 容器已经有 1L 了），5L 容器的水全部倒掉，将 6L 容器的 2L 倒到 5L 容器
    - 6L 容器: 0L
    - 5L 容器: 2L
3. 重复上述步骤，可得到 3L 的水

</details>