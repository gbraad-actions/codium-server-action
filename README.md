Codium Server action
====================

This action runs a remote web extension host based on VS Codium,
that sets up `http://[IP]:8000` for your browser.

```yaml
    - name: Codium Server
      if: ${{ failure() }}
      uses: gbraad-actions/codium-server-action@v1
```

> [!NOTE]
> This actions relies on a service like Tailscale to expose the server to a reachable endpoint
