## Tailwind css   Typography   content practice 

# Html code  usde tailwind css class 

```
     <!-- Font Typography practice  -->
     <p  class="text-xs">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-sm">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-base">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-2xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-3xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-4xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-5xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-6xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-7xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-8xl">The quick brown fox jumps over the lazy dog </p>
     <p  class="text-9xl">The quick brown fox jumps over the lazy dog </p>
 ```
     
##  you  want to change  you can easily. 
<br>

# font Sizes


```
  // tailwind.config.js
  module.exports = {
    theme: {
      fontSize: {
       'xs': '.75rem',
       'sm': '.875rem',
       'tiny': '.875rem',
        'base': '1rem',
        'lg': '1.125rem',
        'xl': '1.25rem',
        '2xl': '1.5rem',
       '3xl': '1.875rem',
       '4xl': '2.25rem',
        '5xl': '3rem',
        '6xl': '4rem',
       '7xl': '5rem',
      }
    }
  }
```

## provive a default line  height css 

```
// tailwind.config.js
module.exports = {
  theme: {
    fontSize: {
      sm: ['14px', '20px'],
      base: ['16px', '24px'],
      lg: ['20px', '28px'],
      xl: ['24px', '32px'],
    }
  }
}
```


# provide  default 
```
// tailwind.config.js
module.exports = {
  theme: {
    fontSize: {
      '2xl': ['24px', {
        letterSpacing: '-0.01em',
      }],
      // Or with a default line-height as well
      '3xl': ['32px', {
        letterSpacing: '-0.02em',
        lineHeight: '40px',
      }],
    }
  }
}
```

    
