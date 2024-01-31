# healthfrontback
/**
 * v0 by Vercel.
 * @see https://v0.dev/t/UHMSAYPMn8B
 * Documentation: https://v0.dev/docs#integrating-generated-code-into-your-nextjs-app
 */
export default function Component() {
  return (
    <>
      <div className="flex flex-col items-center justify-center h-screen bg-green-100">
        <h1 className="text-4xl font-bold text-gray-800">Health Demo</h1>
        <div className="mt-8 p-4 bg-white rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-gray-700">Your Health Status</h2>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h3 className="text-xl font-semibold text-gray-600">75%</h3>
            <p className="mt-2 text-sm text-gray-500">Healthy</p>
            <p className="mt-2 text-sm text-gray-500">
              You are in a good health condition. Keep maintaining your healthy lifestyle.
            </p>
          </div>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h2 className="text-2xl font-semibold text-gray-700">Enter Your Symptoms</h2>
            <textarea
              className="mt-2 p-2 w-full h-20 text-sm text-gray-500 rounded-lg border border-gray-300"
              placeholder="Describe your symptoms..."
            />
            <div className="mt-4 p-4 bg-gray-300 rounded-lg">
              <h4 className="text-lg font-semibold text-gray-600">Symptoms Description</h4>
              <p className="mt-2 text-sm text-gray-500">Enter your symptoms to get a description.</p>
            </div>
          </div>
        </div>
      </div>
      <div className="flex flex-col items-center justify-center h-screen bg-yellow-100">
        <h1 className="text-4xl font-bold text-gray-800">Health Demo</h1>
        <div className="mt-8 p-4 bg-white rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-gray-700">Your Health Status</h2>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h3 className="text-xl font-semibold text-gray-600">50%</h3>
            <p className="mt-2 text-sm text-gray-500">Dangerous</p>
            <p className="mt-2 text-sm text-gray-500">
              Your health condition is not good. Please consult with a doctor immediately.
            </p>
            <div className="mt-4 p-4 bg-gray-300 rounded-lg">
              <h4 className="text-lg font-semibold text-gray-600">Nearby Hospitals</h4>
              <ul className="mt-2 text-sm text-gray-500">
                <li>Hospital A</li>
                <li>Hospital B</li>
                <li>Hospital C</li>
              </ul>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h2 className="text-2xl font-semibold text-gray-700">Enter Your Symptoms</h2>
            <textarea
              className="mt-2 p-2 w-full h-20 text-sm text-gray-500 rounded-lg border border-gray-300"
              placeholder="Describe your symptoms..."
            />
            <div className="mt-4 p-4 bg-gray-300 rounded-lg">
              <h4 className="text-lg font-semibold text-gray-600">Symptoms Description</h4>
              <p className="mt-2 text-sm text-gray-500">Enter your symptoms to get a description.</p>
            </div>
          </div>
        </div>
      </div>
      <div className="flex flex-col items-center justify-center h-screen bg-orange-100">
        <h1 className="text-4xl font-bold text-gray-800">Health Demo</h1>
        <div className="mt-8 p-4 bg-white rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-gray-700">Your Health Status</h2>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h3 className="text-xl font-semibold text-gray-600">25%</h3>
            <p className="mt-2 text-sm text-gray-500">Very Dangerous</p>
            <p className="mt-2 text-sm text-gray-500">
              Your health condition is very dangerous. Please seek medical attention immediately.
            </p>
            <div className="mt-4 p-4 bg-gray-300 rounded-lg">
              <h4 className="text-lg font-semibold text-gray-600">Nearby Hospitals</h4>
              <ul className="mt-2 text-sm text-gray-500">
                <li>Hospital D</li>
                <li>Hospital E</li>
                <li>Hospital F</li>
              </ul>
            </div>
          </div>
          <div className="mt-4 p-4 bg-gray-200 rounded-lg">
            <h2 className="text-2xl font-semibold text-gray-700">Enter Your Symptoms</h2>
            <textarea
              className="mt-2 p-2 w-full h-20 text-sm text-gray-500 rounded-lg border border-gray-300"
              placeholder="Describe your symptoms..."
            />
            <div className="mt-4 p-4 bg-gray-300 rounded-lg">
              <h4 className="text-lg font-semibold text-gray-600">Symptoms Description</h4>
              <p className="mt-2 text-sm text-gray-500">Enter your symptoms to get a description.</p>
            </div>
          </div>
        </div>
      </div>
    </>
  )
}
