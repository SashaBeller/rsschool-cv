# Polina Skripeleva

## Contacts:

- Discord: SashaBeller
- E-mail: polina.skripeleva@icloud.com
- Tel: 617466401

## About myself:

A linguist; currently studing web-developing.

## Code example:

`function declareWinner(fighter1, fighter2, firstAttacker) {
  while (fighter1.health > 0 && fighter2.health > 0) {
    if (firstAttacker === fighter1.name)
      console.log(
        `${fighter1.name} attacks ${fighter2.name}. ${
          fighter2.name
        } has now ${(fighter2.health =
          fighter2.health - fighter1.damagePerAttack)}.`
      );
    else
      console.log(
        `${fighter2.name} attacks ${fighter1.name}. ${
          fighter1.name
        } has now ${(fighter1.health =
          fighter1.health - fighter2.damagePerAttack)}.`
      );
    firstAttacker === fighter1.name
      ? (firstAttacker = fighter2.name)
      : (firstAttacker = fighter1.name);
  }
  if (fighter1.health <= 0)
    return `${fighter2.name}`;
  if (fighter2.health <= 0)
    return `${fighter1.name}`;
}
`
