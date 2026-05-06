<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Chemistry Mastery Lab</title>
    <style>
        :root { --primary: #2c3e50; --secondary: #3498db; --success: #27ae60; --error: #e74c3c; --bg: #f8f9fa; }
        body { font-family: 'Segoe UI', Arial, sans-serif; background-color: var(--bg); color: var(--primary); padding: 20px; }
        .container { max-width: 900px; margin: auto; background: white; padding: 25px; border-radius: 15px; box-shadow: 0 5px 20px rgba(0,0,0,0.1); }
        h1 { text-align: center; border-bottom: 3px solid var(--secondary); padding-bottom: 10px; }
        .nav-menu { display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px; justify-content: center; }
        .nav-btn { padding: 10px 15px; border: 2px solid var(--secondary); border-radius: 8px; background: white; cursor: pointer; font-weight: bold; }
        .nav-btn:hover { background: #ebf5fb; }
        .nav-btn.active { background: var(--secondary); color: white; }
        .instructions { background: #e8f4fd; border-left: 5px solid var(--secondary); padding: 15px; margin-bottom: 20px; border-radius: 4px; font-size: 0.95em; }
        .problem-card { background: #fff; border: 1px solid #eee; padding: 15px; margin-bottom: 10px; border-radius: 8px; display: flex; align-items: center; justify-content: space-between; transition: 0.2s; }
        .problem-card:hover { border-color: var(--secondary); }
        .level-tag { font-size: 0.7em; text-transform: uppercase; padding: 3px 8px; border-radius: 10px; font-weight: bold; margin-right: 10px; }
        .tag-easy { background: #d4edda; color: #155724; }
        .tag-medium { background: #fff3cd; color: #856404; }
        .tag-hard { background: #f8d7da; color: #721c24; }
        input { width: 70px; padding: 8px; border: 2px solid #ccc; border-radius: 5px; text-align: center; margin-right: 10px; }
        .check-btn { padding: 8px 15px; background: var(--primary); color: white; border: none; border-radius: 5px; cursor: pointer; }
        .feedback { font-weight: bold; margin-left: 10px; width: 100px; display: inline-block; }
        .print-section { text-align: center; margin-top: 30px; padding-top: 20px; border-top: 2px dashed #ccc; }
        .print-btn { background: #27ae60; color: white; padding: 15px 40px; font-size: 1.2em; border: none; border-radius: 8px; cursor: pointer; }
        @media print { .nav-menu, .instructions, .print-btn, .check-btn { display: none !important; } .container { box-shadow: none; border: none; } input { border: none !important; border-bottom: 1px solid black !important; } }
    </style>
</head>
<body>

<div class="container">
    <h1>🧪 Chemistry Mastery Lab</h1>
