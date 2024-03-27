# DataRich Tutorial

## Fenced code blocks with code highlighting

`const ExampleCode = () => {
  return <div> .... </div>;
};`


## Table

<FlatUiTable
  data={[
    {
      age: 35,
      firstName: "Jon",
      id: 1,
      lastName: "Snow",
    },
    {
      age: 42,
      firstName: "Cersei",
      id: 2,
      lastName: "Lannister",
    },
    {
      age: 45,
      firstName: "Jaime",
      id: 3,
      lastName: "Lannister",
    },
    {
      age: 16,
      firstName: "Arya",
      id: 4,
      lastName: "Stark",
    },
  ]}
/>

## Chart

<LineChart
  data={[
    [
      '1850',
      -0.41765878
    ],
    [
      '1851',
      -0.2333498
    ],
    [
      '1852',
      -0.22939907
    ],
    [
      '1853',
      -0.27035445
    ],
    [
      '1854',
      -0.29163003
    ]
  ]}
 />

 ## PlotlyBarChart

 <PlotlyBarChart
  data={[
    {
      temperature: -0.41765878,
      year: '1850'
    },
    {
      temperature: -0.2333498,
      year: '1851'
    },
    {
      temperature: -0.22939907,
      year: '1852'
    },
    {
      temperature: -0.27035445,
      year: '1853'
    },
    {
      temperature: -0.29163003,
      year: '1854'
    }
  ]}
  xAxis="year"
  yAxis="temperature"
/>
