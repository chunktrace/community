# ChunkTrace community

Questions, ideas and feedback for [ChunkTrace](https://chunktrace.com), the RAG failure profiler: it replays one query trace through index, filter, threshold, top_k, rerank and context, and names the first stage that lost the chunk the answer needed.

ChunkTrace is new, and what its first users say decides what gets built next.

## Where to post

Everything goes in [Discussions](https://github.com/chunktrace/community/discussions):

- **Ideas**: a failure it should catch, a vector store or framework you need, something that would make a finding clearer.
- **Q&A**: how to instrument your pipeline, how to read a diagnosis, why a trace was diagnosed the way it was.
- **General**: anything else, including "this confused me".

When a question is about a specific diagnosis, the finding's code and its `evidence` are usually enough to answer it. Leave out chunk text and anything else from your own data that should not be public.

## Not here

- **Something private** (your account, billing, a trace you can't share): hello@chunktrace.com.
- **A security problem**: hello@chunktrace.com, not a public post.

## Links

- [Live demo](https://chunktrace.com/demo): three broken traces to take apart, no account needed
- [Docs](https://chunktrace.com/docs/)
- [`@chunktrace/sdk`](https://www.npmjs.com/package/@chunktrace/sdk) and [`@chunktrace/core`](https://www.npmjs.com/package/@chunktrace/core) on npm
