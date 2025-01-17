const marsFacts = [
    {
        title: "Red Planet",
        description: "Mars is often called the 'Red Planet' because of its reddish appearance, which is due to iron oxide, or rust, on its surface."
    },
    {
        title: "Thin Atmosphere",
        description: "Mars has a very thin atmosphere composed mostly of carbon dioxide, with traces of nitrogen and argon."
    },
    {
        title: "Two Moons",
        description: "Mars has two small moons, Phobos and Deimos, which are thought to be captured asteroids."
    },
    {
        title: "Largest Volcano",
        description: "Olympus Mons on Mars is the largest volcano in the solar system, standing about 13.6 miles (22 kilometers) high."
    },
    {
        title: "Deepest Canyon",
        description: "Valles Marineris is a vast canyon system on Mars, over 2,500 miles (4,000 kilometers) long and up to 7 miles (11 kilometers) deep."
    },
    {
        title: "Water Ice",
        description: "Mars has polar ice caps made of water and dry ice (frozen carbon dioxide), and there is evidence of water ice beneath its surface."
    },
    {
        title: "Seasons",
        description: "Mars experiences seasons like Earth due to its tilted axis, but they last about twice as long because a Martian year is 687 Earth days."
    },
    {
        title: "Dust Storms",
        description: "Mars is known for its massive dust storms, which can cover the entire planet and last for weeks."
    },
    {
        title: "Potential for Life",
        description: "Scientists are interested in Mars because of its potential to have harbored life in the past, given evidence of ancient riverbeds and minerals that form in water."
    },
    {
        title: "Exploration",
        description: "Mars has been explored by numerous spacecraft, including rovers like Curiosity and Perseverance, which are studying its surface and climate."
    }
];

const factsList = document.getElementById('facts-list');

marsFacts.forEach(fact => {
    const listItem = document.createElement('li');
    const factTitle = document.createElement('h2');
    const factDescription = document.createElement('p');

    factTitle.textContent = fact.title;
    factDescription.textContent = fact.description;

    listItem.appendChild(factTitle);
    listItem.appendChild(factDescription);
    factsList.appendChild(listItem);
});
