## Change Log

### v3.10.1

07-Dec-2016

Fix a react warning about missing `contentLabel` property [PR66](https://github.com/storybooks/storybook-ui/pull/66)

### v3.10.0

05-Dec-2016

Storybook keyboard shortcuts are disabled when the user is focused into a textarea, input or similar elements. [PR65](https://github.com/storybooks/storybook-ui/pull/65)

### v3.9.0

30-Nov-2016

Some design tweaks to the UI. [PR64](https://github.com/storybooks/storybook-ui/pull/64)

### v3.8.0

16-Nov-2016

Replace the use of Redux with [Podda](https://github.com/arunoda/podda). Now it's pretty easy to work with the system. [PR61](https://github.com/storybooks/storybook-ui/pull/61)

### v3.7.0

13-Nov-2016

Use the new React Komposer. It's a bit more lightweight and high performant. [PR58](https://github.com/storybooks/storybook-ui/pull/58)

### v3.6.4

12-Nov-2016

Avoid preview re-mounting when switching to the full screen mode. [PR59](https://github.com/storybooks/storybook-ui/pull/59)

### v3.6.3

17-Oct-2016

-   Improve shortcut help view for Windows users [PR54](https://github.com/kadirahq/storybook-ui/pull/54)

### v3.6.2

04-Oct-2016

-   Fix a style regression introduced by the previous PR. See: [PR47](https://github.com/kadirahq/storybook-ui/pull/47)

### v3.6.1

29-Sep-2016

-   Use links in story list for accessibility [PR43](https://github.com/kadirahq/storybook-ui/pull/43)

### v3.6.0

27-Sep-2016

-   Dynamic Panel titles [PR42](https://github.com/kadirahq/storybook-ui/pull/42)

### v3.5.0

26-Sep-2016

-   Set layout state with provider api [PR41](https://github.com/kadirahq/storybook-ui/pull/41)

### v3.4.1

2-Sep-2016

-   Call the onStory callback as soon as it listens. [PR38](https://github.com/kadirahq/storybook-ui/pull/38)

### v3.4.0

2-Sep-2016

-   Custom query params are not stored in a separate object. [PR37](https://github.com/kadirahq/storybook-ui/pull/37)

### v3.3.4

30-Aug-2016

-   Add missing react-dom peerDependency [PR35](https://github.com/kadirahq/storybook-ui/pull/35)

### v3.3.3

30-Aug-2016

-   Avoid re-rendering panel content [PR36](https://github.com/kadirahq/storybook-ui/pull/36)

### v3.3.2

24-Aug-2016

-   When some url params are already present ui is displayed in the default way. [PR33](https://github.com/kadirahq/storybook-ui/pull/33)

### v3.3.1

24-Aug-2016

-   Avoid adding custom query params to the state if its undefined. [PR32](https://github.com/kadirahq/storybook-ui/pull/32)
-   Prevent emit story event for every redux store change. [PR31](https://github.com/kadirahq/storybook-ui/pull/31)

### v3.3.0

23-Aug-2016

-   Add 'setQueryParams' and 'getQueryParams' to api. [PR30](https://github.com/kadirahq/storybook-ui/pull/30)
-   Selected down panel in url. [PR29](https://github.com/kadirahq/storybook-ui/pull/29)

### v3.2.0

09-Aug-2016

Support multiple callbacks for the provider's onStory callback.

### v3.1.1

05-Aug-2016

Update react-fuzzy to version 0.3.3.

### v3.1.0

05-Aug-2016

Add support for NPM2.

Basically, we remove the NPM3 from the package.json's engine. We also changed the example app to work with NPM2.

### v3.0.0

-   Remove Action Logger and add support for custom panels [PR22](https://github.com/kadirahq/storybook-ui/pull/22)

### v2.6.1

-   Remove some React warnings due to bad code.

### v2.6.0

-   Remove logger name with the updated react-inspector. [PR21](https://github.com/kadirahq/storybook-ui/pull/21)

### v2.5.0

-   API to set options added. [PR20](https://github.com/kadirahq/storybook-ui/pull/20)
-   Ability to dock action logger in right. [PR18](https://github.com/kadirahq/storybook-ui/pull/18)
-   Add transition to latest added log. [PR16](https://github.com/kadirahq/storybook-ui/pull/16)

### v2.4.0

-   Show cross only if text present in the filter box. [PR13](https://github.com/kadirahq/storybook-ui/pull/13)
-   Update react-fuzzy. [PR12](https://github.com/kadirahq/storybook-ui/pull/12)
-   Improved logging with react-inspector. [PR11](https://github.com/kadirahq/storybook-ui/pull/11)

### v2.3.0

-   Add support for Redux DevTools extension. See [PR8](https://github.com/kadirahq/storybook-ui/pull/8).
-   Add fuzzy search support with a brand new search overlay. See [PR7](https://github.com/kadirahq/storybook-ui/pull/7).

### v2.2.0

-   Add fullscreen and other shortcut state to the URL. See [PR5](https://github.com/kadirahq/storybook-ui/pull/5)

### v2.1.1

-   Add a hacking guide.
-   Refactored the module code base and removed provider code.

### v2.1.0

-   When creating the provider, it's required to extend from the base Provider. See [this example](https://github.com/kadirahq/storybook-ui/blob/master/example/client/provider.js#L10) for more info.

### v2.0.0

-   Expose the whole Manager UI from this module. See the usage in [react-storybook](https://github.com/storybooks/react-storybook/blob/master/src/client/manager/index.js).
