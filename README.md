<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Pokémon Showdown Teams</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        .container { width: 80%; margin: auto; padding: 20px; background-color: #fff; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1 { text-align: center; }
        .footer { text-align: center; margin-top: 20px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Best Pokémon Showdown Teams</h1>
        <p><strong>Created by:</strong> AlexTheSigma</p>
        <p><strong>Special Thanks to:</strong> Ben Alex XD</p>

        <h2>Top Recommended Teams</h2>
        <ul>
            <li><strong>Team 1:</strong> [Details about Team 1]</li>
            <li><strong>Team 2:</strong> [Details about Team 2]</li>
            <li><strong>Team 3:</strong> [Details about Team 3]</li>
        </ul><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Pokémon Showdown Teams</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        .container { width: 80%; margin: auto; padding: 20px; background-color: #fff; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1 { text-align: center; }
        .footer { text-align: center; margin-top: 20px; }
        ul { list-style-type: none; padding: 0; }
        li { margin-bottom: 20px; }
        .team-item { display: flex; align-items: center; }
        .team-item img { width: 150px; height: 150px; object-fit: cover; margin-right: 20px; }
        .team-item div { max-width: 600px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Best Pokémon Showdown Teams</h1>
        <p><strong>Created by:</strong> AlexTheSigma</p>
        <p><strong>Special Thanks to:</strong> Ben Alex XD</p>

        <h2>Top Recommended Teams</h2>
        <ul id="teamList">
            <!-- Teams will be loaded here by JavaScript -->
        </ul>
    </div>
    <div class="footer">
        <p>&copy; 2024 Best Pokémon Showdown Teams</p>
    </div>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            fetch('teams.json')
                .then(response => response.json())
                .then(data => {
                    const teamList = document.getElementById('teamList');
                    data.teams.forEach(team => {
                        const listItem = document.createElement('li');
                        listItem.classList.add('team-item');
                        listItem.innerHTML = `
                            <img src="${team.image}" alt="${team.name}">
                            <div>
                                <strong>${team.name}:</strong> ${team.details}
                            </div>
                        `;
                        teamList.appendChild(listItem);
                    });
                })
                .catch(error => console.error('Error fetching teams:', error));
        });
    </script>
</body>
</html>
Example JSON File (teams.json)
json
Copy code
{
    "teams": [
        {
            "name": "Team 1",
            "details": "Description and strategies for Team 1.",
            "image": "https://example.com/image1.jpg"
        },
        {
            "name": "Team 2",
            "details": "Description and strategies for Team 2.",
            "image": "https://example.com/image2.jpg"
        }
        // Add more teams up to 50
    ]
}
    </div>
    <div class="footer">
        <p>&copy; 2024 Best Pokémon Showdown Teams</p>
    </div>
</body>
</html>
