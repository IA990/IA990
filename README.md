- name: Checkout veille-llm repo
  uses: actions/checkout@v4
  with:
    repository: IA990/veille-llm
    path: veille-llm
    token: ${{ secrets.GITHUB_TOKEN }}
