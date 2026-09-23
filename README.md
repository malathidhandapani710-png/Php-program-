<?php
// Student Marks Management

$marks = array(85, 72, 90, 68, 95);

// Calculate total
$total = array_sum($marks);

// Calculate average
$average = $total / count($marks);

// Find highest and lowest marks
$highest = max($marks);
$lowest = min($marks);

echo "Student Marks Management<br><br>";

echo "Marks: ";
foreach ($marks as $mark) {
    echo $mark . " ";
}

echo "<br>Total Marks: " . $total;
echo "<br>Average Marks: " . $average;
echo "<br>Highest Mark: " . $highest;
echo "<br>Lowest Mark: " . $lowest;
?>
