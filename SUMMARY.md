# Summary

-   [시작하기](docs/getting-started.md)
    -   [왜 타입스크립트인가](docs/why-typescript.md)
-   [자바스크립트](docs/javascript/recap.md)
    -   [비교 연산자](docs/javascript/equality.md)
    -   [참조 연산자](docs/javascript/references.md)
    -   [Null vs. Undefined](docs/javascript/null-undefined.md)
    -   [this](docs/javascript/this.md)
    -   [클로저](docs/javascript/closure.md)
    -   [Number](docs/javascript/number.md)
    -   [Truthy](docs/javascript/truthy.md)
-   [미래의 자바스크립트](docs/future-javascript.md)
    -   [클래스](docs/classes.md)
        -   [즉시실행함수](docs/classes-emit.md)
    -   [화살표 함수](docs/arrow-functions.md)
    -   [나머지 연산자](docs/rest-parameters.md)
    -   [let](docs/let.md)
    -   [const](docs/const.md)
    -   [비구조화 할당](docs/destructuring.md)
    -   [전개 연산자](docs/spread-operator.md)
    -   [for...of](docs/for...of.md)
    -   [이터레이터](docs/iterators.md)
    -   [템플릿 리터럴](docs/template-strings.md)
    -   [프로미스](docs/promise.md)
    -   [제네레이터](docs/generators.md)
    -   [Async Await](docs/async-await.md)
-   [프로젝트](docs/project/project.md)
    -   [컴파일러 제어](docs/project/compilation-context.md)
        -   [tsconfig.json](docs/project/tsconfig.md)
        -   [파일 경로 지정](docs/project/files.md)
    -   [선언](docs/project/declarationspaces.md)
    -   [모듈화](docs/project/modules.md)
        -   [파일을 이용한 모듈화](docs/project/external-modules.md)
        -   [globals.d.ts](docs/project/globals.md)
    -   [네임스페이스](docs/project/namespaces.md)
    -   [동적 표현식 가져오기](docs/project/dynamic-import-expressions.md)
-   [Node.js 시작하기](docs/quick/nodejs.md)
-   [Browser 시작하기](docs/quick/browser.md)
-   [타입스크립트 타입 시스템](docs/types/type-system.md)
    -   [자바스크립트 마이그레이션 가이드](docs/types/migrating.md)
    -   [@types](docs/types/@types.md)
    -   [주변 선언](docs/types/ambient/intro.md)
        -   [파일 선언](docs/types/ambient/d.ts.md)
        -   [변수](docs/types/ambient/variables.md)
    -   [인터페이스](docs/types/interfaces.md)
    -   [열거형(Enums)](docs/enums.md)
    -   [`lib.d.ts`](docs/types/lib.d.ts.md)
    -   [함수](docs/types/functions.md)
    -   [콜러블(Callable)](docs/types/callable.md)
    -   [타입 표명(Type Assertion)](docs/types/type-assertion.md)
    -   [신선도(Freshness)](docs/types/freshness.md)
    -   [타입 가드](docs/types/typeGuard.md)
    -   [리터럴(Literal)](docs/types/literal-types.md)
    -   [읽기 전용(readonly)](docs/types/readonly.md)
    -   [제네릭](docs/types/generics.md)
    -   [타입 인터페이스](docs/types/type-inference.md)
    -   [타입 호환성](docs/types/type-compatibility.md)
    -   [Never 타입](docs/types/never.md)
    -   [구별된 유니온](docs/types/discriminated-unions.md)
    -   [인덱스 서명(Index Signature)](docs/types/index-signatures.md)
    -   [타입 이동하기](docs/types/moving-types.md)
    -   [예외 처리](docs/types/exceptions.md)
    -   [믹스인(Mixin)](docs/types/mixins.md)
-   [JSX](docs/jsx/tsx.md)
    -   [React](docs/jsx/react.md)
    -   [Non React JSX](docs/jsx/others.md)
-   [Options](docs/options/intro.md)
    -   [noImplicitAny](docs/options/noImplicitAny.md)
    -   [strictNullChecks](docs/options/strictNullChecks.md)
-   [타입스크립트 에러](docs/errors/main.md)
    -   [에러 메세지](docs/errors/interpreting-errors.md)
    -   [공통 에러](docs/errors/common-errors.md)
-   [NPM](docs/npm/index.md)
-   [테스트](docs/testing/intro.md)
    -   [Jest](docs/testing/jest.md)
    -   [Cypress](docs/testing/cypress.md)
-   [Tools](docs/tools/intro.md)
    -   [Prettier](docs/tools/prettier.md)
    -   [Husky](docs/tools/husky.md)
    -   [ESLint](docs/tools/eslint.md)
    -   [Changelog](docs/tools/changelog.md)
-   [팁](docs/tips/main.md)
    -   [문자열 Enums](docs/tips/stringEnums.md)
    -   [타입 단언](docs/tips/nominalTyping.md)
    -   [상태 저장 함수](docs/tips/statefulFunctions.md)
    -   [커링](docs/tips/currying.md)
    -   [제네릭 타입 예시](docs/tips/typeInstantiation.md)
    -   [객체 타입 설정](docs/tips/lazyObjectLiteralInitialization.md)
    -   [유용한 클래스](docs/tips/classesAreUseful.md)
    -   [Import / Export](docs/tips/defaultIsBad.md)
    -   [속성 Setters](docs/tips/propertySetters.md)
    -   [`outFile` 주의사항](docs/tips/outFile.md)
    -   [제이쿼리 팁](docs/tips/jquery.md)
    -   [정적 생성자](docs/tips/staticConstructor.md)
    -   [싱글톤 패턴](docs/tips/singleton.md)
    -   [함수 파라미터](docs/tips/functionParameters.md)
    -   [토글 생성](docs/tips/build-toggles.md)
    -   [Import 여러개 하기](docs/tips/barrel.md)
    -   [배열 생성](docs/tips/create-arrays.md)
    -   [생성자에서 타입정의](docs/tips/typed-event.md)
-   [스타일 가이드](docs/styleguide/styleguide.md)
-   [타입스크립트 컴파일러 구조](docs/compiler/overview.md)
    -   [Program](docs/compiler/program.md)
    -   [AST](docs/compiler/ast.md)
        -   [TIP: Visit Children](docs/compiler/ast-tip-children.md)
        -   [TIP: SyntaxKind enum](docs/compiler/ast-tip-syntaxkind.md)
        -   [Trivia](docs/compiler/ast-trivia.md)
    -   [Scanner](docs/compiler/scanner.md)
    -   [Parser](docs/compiler/parser.md)
        -   [Parser Functions](docs/compiler/parser-functions.md)
    -   [Binder](docs/compiler/binder.md)
        -   [Binder Functions](docs/compiler/binder-functions.md)
        -   [Binder Declarations](docs/compiler/binder-declarations.md)
        -   [Binder Container](docs/compiler/binder-container.md)
        -   [Binder SymbolTable](docs/compiler/binder-symboltable.md)
        -   [Binder Error Reporting](docs/compiler/binder-diagnostics.md)
    -   [Checker](docs/compiler/checker.md)
        -   [Checker Diagnostics](docs/compiler/checker-global.md)
        -   [Checker Error Reporting](docs/compiler/checker-diagnostics.md)
    -   [Emitter](docs/compiler/emitter.md)
        -   [Emitter Functions](docs/compiler/emitter-functions.md)
        -   [Emitter SourceMaps](docs/compiler/emitter-sourcemaps.md)
    -   [Contributing](docs/compiler/contributing.md)
