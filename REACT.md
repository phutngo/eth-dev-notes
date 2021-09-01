# REACT 

## Key Concepts

## Favorite Libraries

### Material UI

### React-Query

<https://tkdodo.eu/blog/react-query-data-transformations>

1. In the queryFn - instead of returning the raw data from backend, transform it first, then return. For example:

````js
//async axios call to get the data.
const getBoard = async (credsAndBoardId) => {
  const { data: results } = await axios({
    method: "post",
    url: "/.netlify/functions/board",
    headers: {
      "Content-Type": "application/json",
    },
    data: credsAndBoardId,
  });

  //! instead of directly returning the results, do transform here, then return the transformed results.
  return results;
};
````

3. using the select option is flexible and a good pattern

### Zustand

### Jotai

### React Beautiful DND

[react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd)