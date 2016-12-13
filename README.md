# trailers

SITE GOALS
    Hub offering reminders and alerts of important dates surrounding movies
        When a trailer is added/released (ex. just added new trailer for movie)
        At a certain time relative to a significant date (ex. 1 week before out in theaters)
        When media is available on a new format (ex Game Of Thrones was just added to Netflix)

JSON FORMAT
{
    media = [
        filmA = {
            ... meta ...
            title: ‘the official name of the movie (year)’
            key: ‘imdbKey’
            trailerNames: [‘trailer one’, ‘trailer two’, ‘extended trailer’]
            trailerLinks: [‘trailer one url’, ‘trailer two url’, ‘extended trailer url’]
            genre: [‘Horror’, ’Comedy’, ’Documentary’]
            stars: [‘Arnold Schwarzeneggar’, ‘Judy Dench’, ‘Jim Carrey’]
            ... reference ...
            theaterRelease: ‘January 10th, 2017’
            blurayRelease: ‘October 12th, 2017’
            bluraySale: ‘amazonLinkToBuy’
            4KRelease: ‘October 12th, 2017’
            4KSale: ‘amazonLinkToBuy’
            dvdRelease: ‘’
            dvdSale: ‘’
            amazonVideo: ‘’
            hboGoLink: ‘’
            huluLink: ‘url’
            netflixLink: ‘url’
        }
    ]
}
