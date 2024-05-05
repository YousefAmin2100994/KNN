<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <p>
        K-Nearest Neighbors (KNN) is a simple, non-parametric algorithm used for both classification and regression tasks.
    </p>
    <h2>Main Parameters</h2>
    <ul>
        <li><strong>n_neighbors:</strong> Number of neighbors to consider.</li>
        <li><strong>weights:</strong> Weight function used in prediction (uniform or distance).</li>
        <li><strong>algorithm:</strong> Algorithm used to compute nearest neighbors (auto, ball_tree, kd_tree, or brute).</li>
        <li><strong>leaf_size:</strong> Leaf size passed to BallTree or KDTree.</li>
        <li><strong>p:</strong> Power parameter for the Minkowski metric.</li>
        <li><strong>metric:</strong> Distance metric used for the tree.</li>
    </ul>
    <h2>Classifier-Specific Parameters</h2>
    <ul>
        <li><strong>n_jobs:</strong> Number of parallel jobs to run for neighbors search.</li>
    </ul>
    <h2>Regressor-Specific Parameters</h2>
    <ul>
        <li><strong>metric_params:</strong> Additional keyword arguments for the metric function.</li>
    </ul>
    <p>
        These parameters allow you to control various aspects of the KNN model, such as the number of neighbors, the weighting of neighbors, the algorithm used to compute neighbors, and the distance metric. Depending on your data and problem, you may need to adjust these parameters to achieve the best performance.
    </p>
</body>
</html>
