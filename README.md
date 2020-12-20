# ts-react-snippets

react typescript snippets


|  表头   | 表头  |
|  ----  | ----  |
| tb-cc  | React Class Component  |
| tb-cpc | React Class PureComponent |
| tb-fc  | React FunctionComponent |

## example

1. **tb-cc**
```jsx
import React from 'react'

type Props = {}

type State = {}

export class ComponentName extends React.Component<Props, State> {
  render() {
    
  }
}

```

2. **tb-cpc**
```jsx
import React from 'react'

type Props = {}

type State = {}

export class ComponentName extends React.PureComponent<Props, State> {
  render() {
    
  }
}

```

3. **tb-fc**
```jsx
import React, { FC } from 'react'

type Props = {}

export const ComponentName: FC<Props> = (props) => {
  return (
    
  )
}

```



