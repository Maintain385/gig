# gig
weekly schedule for Dolly
Dolly is a stock trader & goes to the gym
//
const day = 'sunday';

switch (day) {
    case 'monday': // day === 'monday'
        console.log('trade stocks');
        console.log('goto the gym');
        break;
    case 'tuesday':
        console.log('trade stocks');
        break;
    case 'wednesday':
    case 'thursday':
        console.log('off day goto soccer field');
        break;
    case 'friday':
        console.log('0dte lotto day');
        break;
    case 'saturday':
    case 'sunday':
        console.log('Enjoy the weekend :D');
        break;
    default:
        console.log('not a valid day');
}
