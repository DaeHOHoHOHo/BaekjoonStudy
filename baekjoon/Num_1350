#include <cstdio>
using namespace std;

int main() {

    int n, i;
    long long total, ans, cnt = 0;

    scanf("%d", &n);
    long long arr[n];

    for (i = 0; i < n; i++) scanf("%lld", &arr[i]);
    scanf("%lld", &total);

    for (i = 0; i < n; i++) {
        if (arr[i] > 0 && arr[i] <= total) cnt++;
        else if (arr[i] > total) {
            if (arr[i] % total == 0) cnt += arr[i] / total;
            else cnt += (arr[i]/total) + 1;
        }
    }
    ans = total * cnt;
    printf("%lld\n", ans);

    return 0;
}
