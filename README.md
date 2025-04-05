# OfficialAIagent fine tune custom likeness agent with bunch of use cases.

1. custom fine tune likeness



npm install replicate


Set the REPLICATE_API_TOKEN environment variable:
export REPLICATE_API_TOKEN=r8_Agx**********************************

Visibility

training nodejs

This is your Default API token. Keep it to yourself.

Import and set up the client:
import Replicate from "replicate";

const replicate = new Replicate({
  auth: process.env.REPLICATE_API_TOKEN,
});
