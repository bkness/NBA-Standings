# NBA-Standings
A rapid api that grabs the requested teams stats and displays them for the user to see and select through years I also plan to incorporate another api called giphy into it for extra experience. This is going to be a fun journey and I can tell that coding is only really finally starting!







    button.classList.add('team-button');
    button.dataset.teamid = team.id;
    button.innerText = team.name;
    teamContainer.appendChild(button);

    button.addEventListener('click', function () {
      console.log('click');
      var teamId = this.dataset.teamid;
      searchTeamStandings(teamId);