## Project 01 - Covid Map Dashboard
This is a part of [#50reactproject](https://50reactprojects.com) -- a series of project briefs and wireframes for learning React.

## Brief
Dealing with a global pandemic means that viruses like the Cornovirus impact the world differently based on geographic location.

Having a map with a breakdown of each country's statistics is a useful way of being able to determine things like which countires have been impacted the most.

## Level 1
The easiest way to see statistics coutnry to country is to have a map that you can browse with each country's statistics vailable next to that country.

Create a mapping app that uses the disease.sh Coronavirus API to add markers to the mapp for each country along with the number of COVID-19 cases.

## Level 2
While having the statistics for each country is helpful, it might be useful to be able to compare those statistics to the number of cases in the entire world.

Add a statistics dashboard that shows the number of COVID-19 cases around the world as well as any other useful statistics from the API.

## Level 3
Getting current statistics is a good way to understand the current state of the world, but how does that compare historically?

Use the historical data API to show graphs on the dashbaord that provide context to the growth and spread of the virus.

## To Do
- [ ] Create a new mapp app
- [ ] Fetch API countries data
- [ ] Add markers to map
- [ ] Add statistics to markers
- [ ] Fetch API global data
- [ ] Create a stats dashboard
- [ ] Add global stats
- [ ] Fetch API historical data
- [ ] Add graphs to map

## Toolbox
- [Open Disease Data API](https://disease.sh/) (disease.sh)
- [React Leaflet](https://react-leaflet.js.org/) (React Map component react-leaflet.js.org)
- [Gatsby Leaflet Starter](https://github.com/colbyfayock/gatsby-starter-leaflet) (github.com)

## Inspiration
- [COVID-19 Dashboard by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University (JHU)](https://coronavirus.jhu.edu/map.html) (coronavirus.jhu.ed)
- [Coronavirus (COVID-19) Dashboard Demo](https://coronavirus-map-dashboard.netlify.app/) (coronavirus-map-dashboard.netlify.app)

## Layout Idea
![Layout Wireframe](/public/images/layout-wireframe-idea.jpg)

## Running the application

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
