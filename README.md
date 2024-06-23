# FIFO
<h2> Implementation of FIFO using Page Replacement Algorithm in C</h2>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIFO (First In, First Out)</title>
</head>
<body>
    <h1>FIFO (First In, First Out)</h1>
    <p>FIFO is an acronym for First In, First Out. It is a method for processing and retrieving data where the oldest entries, or the first ones entered, are processed first. In the context of a queue, it means the element added first will be removed first.</p>

    <h2>Principle</h2>
    <p>The FIFO principle is commonly used in various computing and business scenarios where order and time of entry are crucial. For example:</p>
    <ul>
        <li><strong>Data Structures:</strong> In queues, the element that enters first is the one that gets processed and removed first.</li>
        <li><strong>Operating Systems:</strong> FIFO scheduling algorithm where the first process to request the CPU is the first to get executed.</li>
        <li><strong>Inventory Management:</strong> Products are sold in the order they are added to inventory to ensure freshness and minimize storage time.</li>
    </ul>

    <h2>Example</h2>
    <p>Consider a queue of customers waiting in line:</p>
    <ul>
        <li>Customer A arrives first.</li>
        <li>Customer B arrives second.</li>
        <li>Customer C arrives third.</li>
    </ul>
    <p>According to the FIFO principle, they will be served in the following order:</p>
    <ul>
        <li>Customer A is served first.</li>
        <li>Customer B is served second.</li>
        <li>Customer C is served third.</li>
    </ul>
</body>
</html>

