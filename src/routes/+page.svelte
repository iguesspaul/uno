<script>
    class Card {
        constructor(number, color) {
            this.number = number;
            this.color = color;
        }
    }

    let usedCards = [];
    let playerCount;
    let name = "dr.wulf";
</script>

<input bind:value={playerCount} placeholder="player count" />
<h1>{playerCount}</h1>
<h2>{name}</h2>