# Who am I?

Welcome to my GitHub profile! Whilst I do analytics all the way *to the moon*, most know me for being lead on the osu!taiko pp committee!

## About Me

I work on various exciting projects and am always keen to learn new technologies and improve my skills. You can reach me at [jay@ltca.pro](mailto:jayl@ltca.pro).

### Roles
- **osu!taiko pp committee**: Leading the development and balance of osu!taiko's performance points and star rating system.
- **Data Evaluation**: Conducting data analysis and evaluation to support project decisions regarding off-planet activities.
- **Photo Technologies**: Further pushing large-scale photo analysis and systems in the tourism industry.

## Recent Major reworks to osu!taiko

Here are some of my notable contributions:

- **[Rewrite of the `Rhythm` Skill within osu!taiko](https://github.com/ppy/osu/pull/31284)**: Reworked rhythm difficulty based on interval ratios, penalised consistent intervals within rhythm, and introduced new rhythm data classes.

- **[Add `consistentRatioPenalty` to the `Colour` skill](https://github.com/ppy/osu/pull/31285)**: Evaluated a consistency penalty based on rhythmic ratios and implemented a consistency check and penalty calculation.

- **[Improve convert considerations in osu!taiko](https://github.com/ppy/osu/pull/31546)**: Removed conditional convert nerf to star rating, focused on stamina, and disabled the `mono` note buff in stamina.

_For a full list of my contributions, check out my [merged pull requests](https://github.com/pulls?q=is%3Apr+author%3ALawtrohux+is%3Aclosed&sort=updated&order=desc)._

## Setup Instructions

To set up and check changes for yourself for taiko, follow the instructions below!

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Lawtrohux/osu.git
   cd osu
   git checkout (insert branch name here)
   uselocalosu.sh

   git clone https://github.com/ppy/osu-tools.git
   cd osu-tools
   cd PerformanceCalculatorGui
   dotnet run
