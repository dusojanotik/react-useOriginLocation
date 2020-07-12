# React useOriginLocation

## Intro

Simple hook to get the original location of your site. End of using annoying **window**.

## Installation

First, add `useOriginLocation` to your project.

```
$ yarn add react-use-origin-location
or
$ npm install --save react-use-origin-location
```

## Usage

`useOriginLocation` returns an origin location of your site.

```javascript
import useOriginLocation from 'react-use-origin-location';

const MyComponent = () => {
    const location = useOriginLocation();
    return (
        <div className="MyApp">
            {console.log(location)}
        </div>
    );
};

export default MyComponent;
```

# License

MIT License of course.
