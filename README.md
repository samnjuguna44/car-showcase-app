This is a [Next.js](https://nextjs.org/) project tht allows users to rent cars. It uses an API from RaidAPI client to provide the cars and an API from Imagin.studio to provide images for the cars in all angles.

## CAR SHOWCASE APP

Discover the best cars in the world for rental

NOTE:

Nextjs has a bug updating search params resets scroll position.
Solution: change the app to client side rendering - use useState and useEffect.
I used default car image from IMAGEIN STUDIO since their services are not free
I load the placeholder image on error from imagein studio car image url
Solution: pay for imagein studio or get another free service.( still looking for one)
SAMPLE ENV:

NEXT_PUBLIC_RAPID_API_KEY='RAPI API KEY' NEXT_PUBLIC_IMAGIN_API_KEY='API KEY'

THEN:

yarn/npm install yarn/npm run dev
