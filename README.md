# b<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bodybuilding Workout App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        .workout-list {
            list-style-type: none;
            padding: 0;
        }
        .workout {
            background: #ecf0f1;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .workout h2 {
            margin: 0;
            color: #e74c3c;
        }
        .workout img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .video {
            margin: 10px 0;
        }
        .workout-plan {
            margin: 20px 0;
            padding: 15px;
            background: #bdc3c7;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

    <h1>Bodybuilding Workout App</h1>

    <ul class="workout-list">
        <li class="workout">
            <h2>1. Deadlift</h2>
            <img src="https://via.placeholder.com/400x250?text=Deadlift" alt="Deadlift">
            <p>A compound exercise that works multiple muscle groups including back, legs, and core.</p>
            <div class="video">
                <video width="320" height="240" controls>
                    <source src="https://www.example.com/deadlift-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </li>
        <li class="workout">
            <h2>2. Squat</h2>
            <img src="https://via.placeholder.com/400x250?text=Squat" alt="Squat">
            <p>Targets the quadriceps, hamstrings, glutes, and lower back, essential for building leg strength.</p>
            <div class="video">
                <video width="320" height="240" controls>
                    <source src="https://www.example.com/squat-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </li>
        <li class="workout">
            <h2>3. Bench Press</h2>
            <img src="https://via.placeholder.com/400x250?text=Bench+Press" alt="Bench Press">
            <p>Focuses on the chest, shoulders, and triceps, a classic upper body strength exercise.</p>
            <div class="video">
                <video width="320" height="240" controls>
                    <source src="https://www.example.com/bench-press-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </li>
        <li class="workout">
            <h2>4. Pull-Up</h2>
            <img src="https://via.placeholder.com/400x250?text=Pull-Up" alt="Pull-Up">
            <p>An effective bodyweight exercise for the back and biceps, promoting upper body strength.</p>
            <div class="video">
                <video width="320" height="240" controls>
                    <source src="https://www.example.com/pull-up-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </li>
        <li class="workout">
            <h2>5. Overhead Press</h2>
            <img src="https://via.placeholder.com/400x250?text=Overhead+Press" alt="Overhead Press">
            <p>Strengthens shoulders, upper chest, and triceps, also improves stability and core strength.</p>
            <div class="video">
                <video width="320" height="240" controls>
                    <source src="https://www.example.com/overhead-press-video.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </li>
    </ul>

    <div class="workout-plan">
        <h2>In-Depth Workout Plan</h2>
        <p><strong>Week 1:</strong></p>
        <ul>
            <li><strong>Day 1:</strong> Deadlift, Pull-Up, Bench Press (3 sets of 8-10 reps each)</li>
            <li><strong>Day 2:</strong> Squat, Overhead Press, Lunges (3 sets of 8-10 reps each)</li>
            <li><strong>Day 3:</strong> Rest or Light Cardio</li>
            <li><strong>Day 4:</strong> Repeat Day 1 (Increase weight by 5-10 lbs if possible)</li>
            <li><strong>Day 5:</strong> Repeat Day 2 (Increase weight by 5-10 lbs if possible)</li>
            <li><strong>Day 6:</strong> Rest</li>
            <li><strong>Day 7:</strong> Optional Active Recovery (yoga, stretching)</li>
        </ul>
        <p><strong>Week 2:</strong> Adjust reps/sets based on your progress. Aim for progressive overload.</p>
    </div>

    <footer>
        <p>&copy; 2024 Bodybuilding Workout Program</p>
    </footer>

</body>
</html>
