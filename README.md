# Bowling Game Score Calculator
This allows you to calculate the score for a bowling game.

### Example:
```php
<?php

require 'vendor/autoload.php';

$game = new BowlingGame();

for($i = 0; $i < 10; $i ++) {
	$game->roll(7);
	$game->roll(2);
}

echo $game->score(); // Outputs 90 as the score
```