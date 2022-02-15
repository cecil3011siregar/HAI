# HAI
import Image from 'next/image'

function Home() {
  return (
    <>
      <h1>My Homepage</h1>
      <div className="m-2 w-10 sm:w-20 self-center">
        <Image
            src="/Profile.jpg"
            alt="Picture of the author"
            width={500}
            height={500}
        />
      </div>
      <p>Welcome to my homepage!</p>
    </>
  )
}

export default Home
