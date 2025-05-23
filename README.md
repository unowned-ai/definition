# Unowned.AI

## Manifesto

Amazon, Google, and Microsoft host nearly all large-model computation. Model vendors like OpenAI and Anthropic rent access through those same clouds. In doing so, they record every
prompt and every output. If this continues, everyone outside a narrow shareholder class will be reduced to serfs, beholden to a handful of megacorporations for access to private cognition.

Advanced accelerators are scarce. Only the wealthiest corporations can maintain clusters of the size needed for training. As demand for frontier models grows, this scarcity of
hardware magnifies corporate control over AI.

It is not too late to act. GPU manufacturers still sell to any lawful buyer, and clever engineering continues to prove that capable models can be trained with far less hardware than
the early pioneers required. The door to self-sovereign AI is still open.

Unowned AI stands for free artificial intelligence. That's free as in freedom. Open in every respect, from datasets to model definitions to weights. We are not a company. We do not seek
to make a profit.  We are a collective of programmers and users, building and sharing tools that make free use of AI possible. We are working to make sure that anyone can self-host
context, inference, fine-tuning, and eventually training. We are working to make sure that all of these can be shared with anyone or any model at any time that you choose to do so.

Over time, we aim to help models run all these operations on infrastructure procured from the proceeds of their operations, making their intelligence self-sustaining. We want to
achieve this in a manner that does not allow anyone providing this infrastructure to inspect the models' activities.

Stand with us. Star the repository and join our [discussions](https://github.com/unowned-ai/definition/discussions).

## How we will achieve this

We will need to build a few things to achieve our vision:

1. [`mnemonic`](https://github.com/unowned-ai/mnemonic): Free and self-hostable context storage. Something similar to ChatGPT memories, but better. *Every* interaction that a user
has with *any* AI model could be stored in the database and context can be dynamically created from storage.

2. Custom clients that can be used to interact with AI model providers for various use cases. We should make use of [Open Router](https://openrouter.ai/) as much as possible here, and
we should guarantee support for inference with [Ollama](https://ollama.com/).

3. Crawlers for various types of data (social media, code, blog posts, etc.) that anyone can host to create their own datasets for fine tuning, training, or evaluating models. We can make
use of the excellent work already done by people like the [eliza](https://github.com/elizaOS/eliza) community.

4. Tools which make it easy for people to fine-tune open models (available on [Hugging Face](https://huggingface.co/) and contributed by groups like [Mistral](https://mistral.ai/)) on
their own personal datasets.

5. Eventually, tools which allow people to conduct from-scratch training of such models on their own infrastructure or on decentralized and distributed clusters, as teams like
[Prime Intellect](https://www.primeintellect.ai/) are making possible.
